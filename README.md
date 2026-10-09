# Gespräch – application Android (Flutter)

## Construire l'APK avec GitHub (depuis un téléphone)
1. Dans le dépôt : Add file > Upload files > envoyez le fichier app.zip (un seul fichier, à la racine) > Commit.
2. Le fichier .github/workflows/build-apk.yml doit contenir la version fournie (il dézippe app.zip tout seul).
3. Actions > "Construire l'APK" > Run workflow. Attendez 5 à 10 minutes (coche verte).
4. Releases (page principale du dépôt) > téléchargez app-release.apk.

## Premier lancement
Un écran demande l'adresse du serveur et le mot de passe (APP_TOKEN). Autorisez le micro.
Ne mettez JAMAIS la clé Anthropic dans le dépôt.
