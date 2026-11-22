# Skill-and-You-se-perfectionner-en-HTML-CSS-4

Exercice : modernisation du site vitrine de 4 pages 

# 📚 Librairie L'Indépendante

Site vitrine statique réalisé dans le cadre d'un projet d'entraînement en développement web front-end (HTML5 / CSS3). Il présente une librairie indépendante fictive, sa sélection littéraire du mois et des citations philosophiques.

## ✨ Fonctionnalités & Pages

- **Accueil (`accueil.html`)** : Présentation générale de la librairie et accès rapides vers les rubriques principales.
- **Présentation (`presentation.html`)** : Histoire et ambiance de la boutique, accompagnées des horaires d'ouverture.
- **Nos coups de cœur (`coups-de-coeur.html`)** : Sélection de livres classés par catégories (*Classiques* et *Romans*) avec navigation par ancres internes.
- **Extraits choisis (`extraits-choisis.html`)** : Recueil de citations et d'aphorismes (Nietzsche, Montaigne, Machiavel).

## 🛠️ Technologies & Choix techniques

- **HTML5 sémantique** : Structuration claire avec `<header>`, `<nav>`, `<main>`, `<article>`, `<blockquote>` et `<footer>`.
- **CSS3 moderne** :
  - Approche **Mobile-First** avec point de rupture à `768px` pour tablettes et ordinateurs.
  - Mises en page flexibles via **Flexbox** et **CSS Grid** (`auto-fit` / `minmax`).
  - Variables CSS (`:root`) pour une palette éditoriale cohérente (tons papier et bordeaux).
  - Typographies Google Fonts : *Lora* (titres et citations) et *Plus Jakarta Sans* (corps de texte).

## 📁 Structure du projet

```text
librairie-independante/
├── img/
│   ├── bandeau.jpg
│   └── favicon.png
├── accueil.html
├── presentation.html
├── coups-de-coeur.html
├── extraits-choisis.html
├── style.css
└── README.md
