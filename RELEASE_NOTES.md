# SmartSplit AI 0.6.9

## Préparation plus simple

- Trois niveaux de contrôle : **Automatique**, **Assisté** et **Manuel**.
- Le mode automatique garde les réglages techniques hors du parcours principal.
- Les estimations de surplomb, stabilité, supports, matière et durée sont visibles avant export.

## Placement et plateaux fiabilisés

- Placement par silhouette vérifié, avec replis sûrs si une proposition présente un chevauchement.
- Les pièces indépendantes d'un même 3MF disposent de plateaux distincts et peuvent être sélectionnées séparément.
- Chaque pièce est reposée à Z = 0 et contrôlée contre les limites du plateau.
- Les orientations instables ou à faible surface d'appui sont signalées clairement.

## Ajustements manuels utiles

- Déplacement direct à la souris, rotation à 90°, changement de plateau et verrouillage d'une pièce.
- Réoptimisation limitée aux pièces non verrouillées.
- Annuler/Rétablir fonctionne aussi pour les placements.

## Stabilité et sécurité

- Les imports successifs de gros modèles libèrent correctement les anciennes ressources 3D.
- La réparation refuse désormais toute opération qui déformerait fortement le modèle et conserve l'original.
- Les contrôles de centrage, d'appui, de collision, d'export et de mise à jour ont été renforcés.
