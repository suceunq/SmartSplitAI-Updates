# SmartSplit AI 0.8.0 — Release stable

## Nouveau systeme de mise a jour
- Dialogue « Nouvelle version disponible » avec boutons Installer / Plus tard.
- Barre de progression pendant le telechargement.
- Telechargement silencieux en arriere-plan si « Plus tard ».

## Correctifs de stabilite
- Pieces posees sur le plateau (Z=0) sans flottement.
- Filtre des micro-debris / tenons isoles apres decoupe.
- Packing multi-pieces par plateau.
- Camera 360° degrippee (polar angle libre).
- Plateau personnalise (saisie X/Y/Z libre).
- Echelle en pourcentage (plus de pouces).
- parseVersion corrige (les mises a jour fonctionnent).

## Architecture
- Monorepo apps/desktop uniquement (legacy obj-slice supprime).
- Worker timeouts pour eviter les freezes gros modeles.
- Controle pre-export (hors plateau, hauteur, appui).
- CI stricte.

Installateur : SmartSplit_AI_Setup_0.8.0.exe
