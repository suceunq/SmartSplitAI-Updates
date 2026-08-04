# SmartSplit AI 0.6.0

## Placement et préparation automatique

- Les modèles sont automatiquement recentrés sur X/Y et posés exactement à Z=0 après une mise à l’échelle ou une rotation.
- Les pièces générées ne restent plus à 0,6 mm au-dessus du plateau.
- Nouvelle validation géométrique après placement : pièce flottante, sous le plateau, hors zone, instable ou avec une surface d’appui faible.
- Le nesting utilise désormais la silhouette projetée des pièces et non plus uniquement leur rectangle englobant.
- Plusieurs orientations et propositions de coupe sont comparées en privilégiant le nombre minimal de plateaux.
- Sur le modèle de régression Gatto à 450 mm pour la Snapmaker U1, la préparation passe de 5 plateaux à 4.

## Sélection des corps

- Dans un fichier contenant plusieurs objets, chaque corps peut être marqué « à découper ».
- Les corps non sélectionnés restent intacts, mais sont automatiquement orientés, placés et inclus dans les exports.
- La sélection peut aussi être modifiée par double-clic dans la vue 3D.

## Mise à jour et interface

- Barre de progression réelle du téléchargement avec pourcentage.
- Vérification Ed25519 du manifeste et SHA-256 des installateurs avant exécution.
- Téléchargement reprenable, installation silencieuse, redémarrage automatique, journal et rollback vers la version 0.5.0 si le premier démarrage échoue.
- Nouvelle fenêtre « À propos » avec version, licence, lien officiel et vérification manuelle.
- Thèmes clair, sombre et automatique selon Windows, appliqués à l’interface et aux fenêtres secondaires.
- Fenêtre de nouveautés affichée une seule fois après l’installation réussie.

## Stabilité et sécurité

- Contrôles renforcés des limites de plateau et des collisions par silhouette.
- Les sources, journaux, fichiers locaux et secrets restent exclus du dépôt de distribution.
