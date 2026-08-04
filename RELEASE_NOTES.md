# SmartSplit AI 0.6.4

## Mise à jour plus claire

- La progression du téléchargement est maintenant affichée directement dans la fenêtre de mise à jour.
- Après téléchargement et vérification, SmartSplit demande s’il faut redémarrer immédiatement ou plus tard.
- « Redémarrer maintenant » ferme proprement le logiciel, installe silencieusement la mise à jour et relance automatiquement la nouvelle version.
- « Redémarrer plus tard » conserve le paquet signé pour le prochain lancement.

## Plateau correctement centré

- Après une mise à l’échelle, le plateau est recentré sous l’empreinte basse réelle du ou des modèles.
- Les appendices en hauteur, comme une queue ou des bras écartés, ne décalent plus artificiellement le plateau hors de la zone d’appui.
- Le calcul reste échantillonné sur les maillages lourds afin de préserver la réactivité.

## Stabilité

- Les sorties de diagnostic des autotests ne peuvent plus provoquer d’erreur `EPIPE` dans Electron.
- Le téléchargement reste vérifié par signature Ed25519 et empreinte SHA-256 avant toute installation.
