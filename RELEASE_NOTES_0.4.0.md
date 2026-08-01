# SmartSplit AI 0.4.0

## Nouvelles fonctions (parité Split3r étendue)

- **Mode assemblage creux + tenons séparés** (hollow-loose) : cavités sur les deux faces, tenons exportés comme pièces jaunes.
- **Tenon personnalisé STL** : importez votre forme de joint.
- **Extract région** : découpe une tranche (axe + position + épaisseur) avec joints.
- **Analyse maillage détaillée** : triangles, bbox, volume, bords/trous, non-manifold.
- **Rotations 90°** X/Y/Z sur le modèle source.
- **Catalogue imprimantes** encore élargi.
- Labels / repères, pré-split, pyramidaux (déjà en 0.3).

## Technique

- Worker : `assemblyMode`, `custom`, `extract`, `analyze`.
- UI 8 étapes.
