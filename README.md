# Write Up

[![Built with Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build)

> Une base de documentation et de tutoriels construite avec Astro et Starlight.

## 👤 Auteur

Ce projet est développé et maintenu par **CubicPotato**.

L’objectif est de partager des connaissances, des retours d’expérience et des tutoriels accessibles autour du développement web, de l’administration système et des outils utilisés au quotidien.

## 🎯 Objectifs du projet

Write Up a pour objectifs de :

- centraliser des tutoriels et des notes techniques ;
- expliquer des concepts complexes de manière simple et progressive ;
- conserver une trace des solutions et problèmes rencontrés ;
- partager des bonnes pratiques avec la communauté ;
- proposer une documentation claire, accessible et régulièrement améliorable.

## 🚀 Structure du projet

```text
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   └── docs/
│   └── content.config.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Starlight recherche les fichiers `.md` et `.mdx` dans le dossier `src/content/docs/`. Chaque fichier devient une page accessible depuis le site.

Les images peuvent être ajoutées dans `src/assets/` et les fichiers statiques, comme les favicons, dans `public/`.

## 🧞 Commandes

Toutes les commandes sont exécutées depuis la racine du projet :

| Commande | Description |
| --- | --- |
| `npm install` | Installe les dépendances |
| `npm run dev` | Lance le serveur local sur `localhost:4321` |
| `npm run build` | Génère le site de production dans `dist/` |
| `npm run preview` | Prévisualise le build de production |
| `npm run astro -- --help` | Affiche l’aide de la CLI Astro |

## ✍️ Ajouter un tutoriel

1. Créez un fichier `.md` ou `.mdx` dans `src/content/docs/`.
2. Ajoutez les métadonnées de la page.
3. Rédigez le tutoriel en Markdown ou MDX.
4. Vérifiez le résultat avec `npm run dev`.
5. Lancez `npm run build` avant de publier.

## 🔗 Ressources

- [Documentation Starlight](https://starlight.astro.build/)
- [Documentation Astro](https://docs.astro.build/)
- [Communauté Astro](https://astro.build/chat)
