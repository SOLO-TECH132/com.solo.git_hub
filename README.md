# Documentation du tuto git

## Initialisation du repo

```bash
git init
git remote add origin SSH_REPO
```

## Rediger proprement un commit

```
Titre du commit

description du commit avec l'evolution du projet
```

## Envoyer un commit sur le depot a distance

```bash
git add .
git status
git commit -m "titre du commit"
git push origin main
```

## Creation d'une branche

```bash
git checkout -b NOM_BRANCHE
```