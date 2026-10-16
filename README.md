# EcoArt
EcoArt est un projet d'intégration web complet de 5 pages à réaliser en équipe.  Nous devons analyser les wireframes fournies, les transformer en maquettes avec prototype interactif, puis développer le site web responsive en CSS Pur avec (Grid, Flexbox, Variables CSS, Mobile-First).

##  Maquette Figma - Responsive
Voici la version adaptée pour les écrans de tablette :
- [Voir la maquette Tablette](https://www.figma.com/design/eJPFw2QBbBnVMgmPvTKv0B/EcoArt-Tabel-Version?node-id=15-6303&t=DdnXXq7KX3uycotP-1)

---

##  1. Scrum et Organisation d'équipe
Nous utilisons la méthodologie Scrum pour assurer une progression fluide :
- **Product Backlog & User Stories** : Définition des besoins, objectifs et critères d'acceptation.
- **Découpage & Estimation** : Transformation des User Stories en tâches techniques estimées.
- **GitHub Projects** : Suivi des tâches, statuts, responsables et échéances.
- **Rituels** : Synchronisation via le *Daily Scrum* et *Rétrospective* en fin de cycle.
- **Definition of Done (DoD)** : Validation stricte avant de considérer une tâche comme terminée.

---

## 2. Git et GitHub Workflow
Notre équipe applique des règles strictes de versioning :
- **Git Flow** : 
  - `main` : Production.
  - `develop` : Intégration des nouvelles fonctionnalités.
  - `feature/*` : Développement isolé de chaque tâche.
- **Conventions de commits** : Utilisation de messages standardisés (ex: `feat: add homepage`, `fix: correct mobile layout`).
- **Pull Requests (PR)** : Revue de code (Code Review), corrections et fusions contrôlées.
- **.gitignore** : Exclusion stricte des fichiers temporaires et inutiles.

---

## 3. Design et Conception UI/UX
L'interface a été pensée pour offrir un parcours utilisateur optimal :
- **Design System & Charte Graphique** : Centralisation des couleurs, typographies, logos et iconographie.
- **Composants réutilisables** : Boutons, cartes, formulaires, header et footer partagés entre les 5 pages.
- **Maquettes Responsive** : Déclinaisons Mobile, Tablette et Desktop.
- **Hiérarchie Visuelle** : Contraste et lisibilité pour mettre en valeur les boutons d'action et les contenus clés.

---

##  4. HTML et CSS Natif
Le développement est réalisé entièrement en code natif sans framework externe :
- **HTML Sémantique** : Utilisation rigoureuse des balises (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`).
- **Variables CSS (`:root`)** : Gestion globale du thème (ex: `var(--color-primary)`).
- **Flexbox & CSS Grid** : Alignements fluides en 1D et grilles complexes en 2D pour les cartes.
- **Approche Mobile-First & Media Queries** : Conception adaptative pour toutes les résolutions.
- **Code DRY** : Création de classes communes pour limiter la duplication de code.

---

##  5. Accessibilité et Qualité
La plateforme est conçue pour être accessible à tous les utilisateurs :
- **Navigation au clavier** : Support de `Tab`, `Shift + Tab`, et focus visible (`:focus-visible`).
- **Contraste & Lisibilité** : Vérification stricte des couleurs.
- **Formulaires** : Labels associés (`<label for="...">`), gestion des erreurs et champs obligatoires.
- **Images** : Attributs `alt` pertinents pour les lecteurs d'écran.
- **Contrôle Qualité** : Code HTML valide et audits réguliers (Lighthouse, validateurs W3C).

