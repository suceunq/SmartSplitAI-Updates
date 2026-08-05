# SmartSplit AI 0.6.7

## Résumé de mise à jour corrigé

- Le nom et le numéro de version ne sont plus répétés dans la fenêtre « Mise à jour installée ».
- Le premier titre Markdown des notes est reconnu et retiré lorsque la fenêtre affiche déjà cette version.

## Vue éclatée plus propre

- Les micro-îlots numériques issus de la géométrie ou de l'intersection de plusieurs plans ne deviennent plus des pièces autonomes minuscules.
- Ces détails sont rattachés au morceau imprimable le plus proche sans supprimer ni déplacer leur géométrie.
- Les vrais petits éléments restent séparés lorsqu'ils possèdent une taille et un volume réellement imprimables.

## Validation

- Régression reproduite avec `Gatto+Silvestro.3mf` à 300 % : 3 micro-fragments parasites rattachés, passage de 10 à 7 morceaux utiles.
- Conservation du volume contrôlée, nesting sur 4 plateaux validé et export maintenu disponible.
- 31 tests automatisés validés, dont deux nouveaux tests dédiés aux notes de version et aux micro-îlots.
