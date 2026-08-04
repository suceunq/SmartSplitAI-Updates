# SmartSplit AI 0.6.2

## Mise à jour maîtrisée

- Une fenêtre s’affiche au lancement lorsqu’une nouvelle version est disponible.
- **Mettre à jour maintenant** télécharge et vérifie le paquet, avertit du redémarrage, installe la version puis relance automatiquement SmartSplit AI.
- **Plus tard** télécharge silencieusement la mise à jour et la prépare pour le prochain lancement.
- Une mise à jour différée est de nouveau contrôlée avant installation : signature Ed25519 du manifeste, taille et empreinte SHA-256 du paquet.
- Le paquet de retour arrière reste préparé lorsque la version précédente est disponible.

## Affichage du modèle

- Le plateau reste centré sous la pièce après un redimensionnement, même lorsque le modèle dépasse volontairement le volume d’impression.
- Le modèle est posé précisément sur le plan du plateau après chaque changement d’échelle ou rotation.
- Un repère central discret facilite le contrôle visuel de l’alignement.

## Validation

- Tests de sécurité du stockage différé ajoutés.
- Tests fonctionnels validés avec import 3MF, redimensionnement à 300 %, découpe, connecteurs, nesting multi-plateaux et export.
