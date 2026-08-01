# SmartSplit AI 0.3.0

## Parité fonctionnelle (cœur type Split3r)

- **Tenons pyramidaux** tronqués (base carrée, auto-centrage), choisis en priorité en mode automatique.
- **Densité des tenons** : faible / normale / dense par face de coupe.
- **Pré-split multi-plans** X/Y/Z avec preview et estimation du nombre de morceaux.
- **Labels pièces** au format `X.Y.Z` (style assemblage), noms d’objets 3MF et fichiers d’export.
- **Repère gravé** optionnel (pastille + points) sur chaque morceau.
- **Étiquettes 3D** en vue assemblée / éclatée + export **image PNG** d’assemblage.
- **Catalogue imprimantes** élargi (~45 presets publics) avec recherche.

## Technique

- Worker Manifold : `pyramid`, `connectorDensity`, `forcedPlanes`, `engraveLabels`.
- UI réorganisée en 7 étapes (pré-split avant auto-cut).
