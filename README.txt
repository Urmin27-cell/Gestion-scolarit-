GESTION STOCK, CAISSE & SCOLARITÉ — VERSION PWA POUR VERCEL

FONCTIONNALITÉS AJOUTÉES
- Installation PWA sur Android et ordinateurs compatibles : le bouton « Installer » déclenche la fenêtre native lorsque le navigateur l'autorise.
- Icône de l'application basée sur le logo fourni.
- Fichiers manifest, service worker et cache de démarrage.
- Entrée index.html pour un déploiement simple sur Vercel.

DÉPLOIEMENT VERCEL
1. Décompressez tout le ZIP.
2. Envoyez TOUS les fichiers et le dossier icons/ dans le même dossier racine du projet Vercel.
3. Déployez comme site statique. Aucune commande de build n'est nécessaire si vous déployez ces fichiers statiques tels quels.
4. Ouvrez l'URL HTTPS de Vercel, puis utilisez « Installer » ou le menu du navigateur.

IPHONE / IPAD
Apple ne permet pas aux sites web de lancer directement l'installation. Sur iPhone/iPad, ouvrez le site dans Safari > Partager > Ajouter à l'écran d'accueil > Ajouter. Cette limite vient d'iOS, pas du code de l'application.

IMPORTANT
- La logique métier existante n'a pas été volontairement modifiée ; les ajouts concernent uniquement l'enveloppe PWA, le logo et le déploiement.
- Les données existantes sont stockées dans le localStorage de chaque navigateur/appareil. Elles ne sont pas synchronisées automatiquement entre appareils.
- Pour tester l'installation PWA, utilisez l'URL HTTPS publiée, pas un fichier HTML ouvert localement.
