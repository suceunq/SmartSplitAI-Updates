# SmartSplit AI 0.6.5

## Redémarrage automatique corrigé

- Correction de la variable interne `ELECTRON_RUN_AS_NODE` qui était transmise par erreur à l’application après l’installation.
- La nouvelle version est désormais lancée comme application graphique, confirme son bon démarrage et évite un rollback injustifié.
- Le même nettoyage est appliqué lors d’une récupération automatique vers la version précédente.

## Mise à jour plus claire

- La progression du téléchargement est affichée directement dans la fenêtre de mise à jour.
- Après téléchargement et vérification, SmartSplit demande s’il faut redémarrer immédiatement ou plus tard.
- « Redémarrer maintenant » ferme le logiciel, installe silencieusement la mise à jour et relance automatiquement la nouvelle version.

## Plateau correctement centré

- Après une mise à l’échelle, le plateau est centré sous l’empreinte basse réelle du ou des modèles.
- Les éléments en hauteur ou en porte-à-faux, comme une queue, ne décalent plus le plateau hors des zones d’appui.
