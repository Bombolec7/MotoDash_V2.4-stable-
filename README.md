# MotoDash Web

Adaptation navigateur mobile du tableau de bord Android MotoDash. L’archive conserve aussi le projet Android Studio d’origine dans `android-source/`.

## Tester

Ouvrir `web/index.html` pour vérifier l’interface. Pour utiliser GPS et capteurs sur téléphone, servir le dossier `web/` via HTTPS (ou localhost), ouvrir l’URL dans le navigateur mobile et autoriser la localisation et les capteurs. Sur iOS, toucher START pour accorder l’accès aux capteurs si demandé.

## Limites de la plateforme Web

Les API de capteurs ne sont pas uniformes entre navigateurs et téléphones. Les permissions, l’orientation physique et les axes peuvent différer de l’implémentation Android; tester/calibrer sur le téléphone cible avant usage. L’historique est enregistré dans le stockage local du navigateur.
