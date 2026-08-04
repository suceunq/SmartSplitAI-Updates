# SmartSplit AI 0.6.1

## Correction du recentrage

- Le modèle est désormais recentré à partir de ses limites réellement transformées après chaque changement d’échelle ou rotation.
- Une seconde passe pose exactement le point le plus bas du modèle à `Z=0`.
- Le contrôle automatique exige une erreur de centrage et de contact inférieure à `0,01 mm`.
- Une croix orange matérialise précisément le centre du plateau dans la vue de préparation.
- Lorsqu’un modèle dépasse le plateau sélectionné, les dépassements en largeur, profondeur et hauteur sont maintenant indiqués en millimètres.

Cette correction ne modifie pas le moteur de découpe, les connecteurs, le nesting ou les exports validés dans la version 0.6.0.
