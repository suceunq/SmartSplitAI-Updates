# SmartSplit AI 0.2.0

## Sécurité

- Ajout d’un système de mise à jour automatique avec manifeste Ed25519 signé.
- Vérification SHA-256 de chaque installateur avant exécution.
- Téléchargements HTTPS limités aux domaines officiels de distribution GitHub.
- Reprise des téléchargements interrompus et rollback vers la version précédente si le nouveau démarrage échoue.
- Renforcement du sandbox Electron, des permissions, de la navigation et de la politique CSP.
- Validation et limitation des fichiers importés, des archives 3MF, des messages IPC et des exports.

## Stabilité et performances

- Protection contre les archives 3MF anormalement volumineuses et les coordonnées invalides.
- Validation stricte des paramètres transmis au moteur géométrique.
- Gestion plus sûre des noms, tailles et doublons lors de l’export.
- Instance Windows unique afin d’éviter les ouvertures concurrentes accidentelles.

## Distribution

- Nouvelle identité visuelle pour l’icône Windows.
- Dépendances réalignées et audit de sécurité sans vulnérabilité connue.
