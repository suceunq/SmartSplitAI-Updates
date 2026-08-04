# SmartSplit AI 0.6.6

## Importations successives sécurisées

- Le nouveau modèle est entièrement validé avant la libération du projet courant.
- Un fichier incomplet, corrompu, trop lourd ou non exploitable affiche une erreur sans fermer SmartSplit AI et sans remplacer le modèle déjà ouvert.
- Les calculs géométriques en cours sont annulés proprement avant le remplacement d’une scène.
- Les géométries, matériaux et textures de l’ancien modèle sont libérés afin d’éviter une accumulation de RAM ou de VRAM.

## Aucune fermeture inattendue

- Une mise à jour téléchargée en différé n’est plus installée automatiquement pendant une session de travail.
- Au prochain lancement, SmartSplit affiche « Redémarrer maintenant » ou « Redémarrer plus tard » et attend explicitement la décision de l’utilisateur.
- Le correctif de relance automatique sans `ELECTRON_RUN_AS_NODE` reste actif.

## Centrage après transformation

- Après chaque échelle ou rotation, SmartSplit recalcule les limites réelles du maillage transformé.
- Le centre du volume est aligné avec le centre du plateau sur X et Y.
- Le point le plus bas est posé à Z=0 et le cadrage caméra est recalculé.

## Diagnostics

- Ajout d’un journal local et expurgé pour les erreurs du processus principal, du renderer, des workers Electron et des imports.
- Aucun chemin complet, URL ou secret n’est enregistré dans les messages diagnostiques.
