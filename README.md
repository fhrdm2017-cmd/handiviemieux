# HandiVie+ — Pack PWA & Préparation Play Store

Ce dossier contient les fichiers prêts à mettre à la racine de votre dépôt GitHub Pages :
- `index.html` : application complète (Parler & Écouter, Pass Prioritaire, Pilulier & Jour, Lecteur FALC, Calme & Temps, Loisirs & Jeux, GPS & Lieux PMR localisé autour de vous, Urgence ICE gratuite, abonnement à 2,00 €/mois).
- `manifest.json` : configuration PWA installable sur Android / iOS / Web.
- `sw.js` : service worker de mise en cache hors ligne.
- `icon-192.svg` et `icon-512.svg` : icônes de l'application.

## Étapes pour la publication sur Google Play Store
1. Déposez tous ces fichiers à la racine de votre dépôt et activez **GitHub Pages** (URL en `https://`).
2. Ouvrez **PWABuilder** (pwabuilder.com) ou **Bubblewrap** avec votre URL `https://` pour générer le paquet Android signé (`.aab`) et le fichier `assetlinks.json` à placer dans `/.well-known/assetlinks.json`.
3. Créez un compte développeur sur **Google Play Console**, remplissez les fiches et questionnaires de conformité, puis importez le fichier `.aab`.
