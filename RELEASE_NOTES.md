# SmartSplit AI 0.7.0

## Shipping unique : monorepo `apps/desktop`

- Suppression définitive du legacy `obj-slice-desktop` (double codebase).
- Build / packaging / updater unifiés sur Electron + React + packages TS.

## Stabilité & qualité

- **Timeouts worker** (analyze / split / components) pour éviter les freezes sur gros maillages.
- **Contrôle final avant export** : hors plateau, hauteur, flottement, faible appui — bloque les cas critiques.
- **Rapport d’export** texte généré à côté des 3MF.
- Packing multi-pièces densifié (0°/90°) avec repli one-per-plate.
- Orientation face plane après découpe (déjà en amont) + labels pièces visibles en 3D.
- `update-helper.cjs` copié dans le build (fix installation silencieuse des mises à jour).
- CI stricte : plus de refs obj-slice, plus de bundles commités, helper présent après build.

## Mise à jour

- Canal : `suceunq/SmartSplitAI-Updates`
- Installateur : `SmartSplit_AI_Setup_0.7.0.exe`
- Rollback possible vers 0.6.9
