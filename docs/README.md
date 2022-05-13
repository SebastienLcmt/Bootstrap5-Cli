# Bootstrap 5 project using CLI

A high-class japanese restaurant

[Live Demo](https://sebastienlcmt.github.io/Bootstrap5-Cli/)


## Installation de bootstrap

`npm init`

`npm i bootstrap`

Dans package.json, on crée le script pour l'auto-watch de sass, avec le bon chemin

```json
"sass": "sass sass/global.scss styles/raw/style.css --watch"
```

Et on peut lancer la commande `npm run sass`

## Purge CSS

```npm i purgecss```

Pour chaque fichier html :
```json
"purgecss": "purgecss -css styles/raw/style.css --content index.html script/*.js -o styles/cleaned/home.css"
```

```npm run purgecss```
