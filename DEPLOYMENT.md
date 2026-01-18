# Deployment

## Vercel (Recommandé - le plus simple)

1. Connecter votre repo GitHub `MRDNET12/30days` à Vercel
2. Cliquez sur "Deploy"
3. Ajoutez ces variables d'environnement:
   - `NEXTAUTH_URL`: votre URL Vercel
   - `NEXTAUTH_SECRET`: n'importe quelle chaîne aléatoire

## Render

1. Importez le repo `MRDNET12/30days` sur Render
2. Le fichier `render.yaml` configure automatiquement tout
3. Ajoutez `NEXTAUTH_URL` dans les variables d'environnement

## Variables d'environnement requises

- `NODE_ENV`: `production`
- `DATABASE_URL`: `file:./dev.db` (SQLite)
- `NEXTAUTH_URL`: votre URL de déploiement
- `NEXTAUTH_SECRET`: une chaîne aléatoire
