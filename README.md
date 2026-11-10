# My Body Coach — prototype v0.1

## Contenu
- Tableau de bord calories et macronutriments du jour
- Ajout manuel de repas
- Historique des repas
- Saisie et historique du poids
- Navigation mobile et ordinateur
- Base PWA pour installation sur l'écran d'accueil

## Lancer en local
Ouvrir `index.html` dans un navigateur. Pour tester l'installation PWA, héberger le dossier sur un site HTTPS (le service worker ne fonctionne pas depuis `file://`).

## Installer sur iPhone
Une fois hébergé en HTTPS : ouvrir l'adresse dans Safari > bouton Partager > Sur l'écran d'accueil.

## Limites de cette version
Les données sont stockées localement dans le navigateur (`localStorage`) et ne sont pas synchronisées entre appareils. L'analyse photo, le scan de codes-barres, les comptes utilisateurs et l'API OpenAI ne sont pas encore connectés. Ne jamais placer une clé API OpenAI dans le code côté navigateur : elle devra être protégée côté serveur.

Prototype de suivi informatif, non médical.
