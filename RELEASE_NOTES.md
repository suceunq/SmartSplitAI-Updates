# SmartSplit AI 0.6.3

## Centrage et affichage

- La caméra et le viewport suivent désormais exactement la taille réelle de la fenêtre Windows, y compris après maximisation.
- Le modèle et le plateau restent centrés à toute échelle, même à 300 % et lorsque la pièce dépasse largement la zone imprimable.
- La vue globale ajuste correctement un grand nombre de plateaux.

## Découpe et placement

- Chaque morceau est posé à `Z=0` après son orientation ; les îlots déconnectés ne restent plus suspendus au-dessus du plateau.
- Les orientations instables sont écartées avant le nesting.
- La limite de morceaux s’adapte aux modèles extrêmes et les assemblages CAO complexes restent traitables sans bloquer l’interface.
- Correction d’une double libération mémoire lors du rejet d’un connecteur sur une coupe complexe.

## Réparation des maillages

- Le bouton de réparation referme réellement les boucles de bord avant la découpe.
- Les volumes non-manifold sont reconstruits séparément, puis réunis sans perdre leur topologie lors d’un agrandissement important.
- Les surfaces sans volume imprimable et les îlots inférieurs à la précision numérique n’interrompent plus tout le projet.

## Performances et validation

- Suppression d’une recomposition géométrique redondante avant la première proposition automatique.
- Validation automatique renforcée : centrage, contact plateau, chevauchements, limites, export et réactivité.
- Six modèles réels STL/3MF ont été testés à 300 %, dont un STL d’environ un million de triangles et plus de 3 000 sous-volumes.
