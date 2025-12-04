# Déploiement du site

Ce dépôt contient un site statique (fichier `index.html`). Le workflow GitHub Actions `pages.yml` a été ajouté pour déployer automatiquement le contenu du dépôt sur GitHub Pages lorsque vous poussez sur la branche `main`.

Étapes pour finaliser le déploiement :

1. Validez les fichiers créés localement et poussez sur `main` :

```bash
git add -A
git commit -m "Ajout du workflow GitHub Pages"
git push origin main
```

2. Après le push, GitHub Actions déclenchera le workflow `Deploy to GitHub Pages` qui publiera le contenu sur GitHub Pages. L'URL publique sera généralement :

```
https://<votre-utilisateur-ou-organisation>.github.io/<nom-du-repo>/
```

Dans votre cas probable : `https://killianopso-actionimmo.github.io/antoine-dimey/` (disponible une fois l'action terminée et la configuration Pages activée).

3. Si vous souhaitez que je pousse et déclenche l'action depuis cet environnement, autorisez-moi à exécuter les commandes `git` et je procéderai au push.

Si vous préférez une autre plateforme (Netlify, Vercel), dites-moi laquelle et je préparerai la configuration correspondante.
