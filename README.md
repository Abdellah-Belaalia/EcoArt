# EcoArt
EcoArt est un projet d'intégration web complet de 5 pages à réaliser en équipe.  Nous devons analyser les wireframes fournies, les transformer en maquettes avec prototype interactif, puis développer le site web responsive en CSS Pur avec (Grid, Flexbox, Variables CSS, Mobile-First).

##  Maquette Figma - Responsive
Voici notre charte graphique ainsi que les maquettes adaptées aux différents écrans :
- [Voir la maquette Tablette](https://www.figma.com/design/eJPFw2QBbBnVMgmPvTKv0B/EcoArt-Tabel-Version?node-id=15-6303&t=DdnXXq7KX3uycotP-1)
- [Voir la maquette Desktop](https://www.figma.com/design/pyZUNdSx3f6sZ1SfazFamN/EcoArt-Prototype?node-id=1-2&t=jvVrr0E1cjALKnI8-0)
- [Voir la Charte Graphique](https://www.figma.com/design/iteavgcgF8ZxW1zyrmcKkY/Untitled?node-id=0-1&p=f&t=Um3mCnPJIGLk8kNV-0)

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

## ⚙️ 1. Git & Workflow

### Git Configuration & Projet
- **Git Project** : Dépôt central hébergeant le code source et l'historique des versions.
- **Git Configuration** : Configuration des environnements locaux et des droits d'accès pour les collaborateurs.

### Git Configuration Branches & Git Flow
Nous adoptons la méthodologie **Git Flow** pour garantir une collaboration sans conflit et une intégration continue :
- `main` : Branche de production contenant uniquement le code stable et validé.
- `dev` : Branche de développement principal (intégration de toutes les features).
- `feature/*` : Branches créées à partir de `dev` pour développer des fonctionnalités spécifiques (ex: `feature/mariem`).

---


##  2. Design et Conception

### Charte Graphique
Le projet suit une charte graphique stricte pour garantir la cohérence visuelle de l'application (typographie, iconographie, espacements).

### Variables CSS
Toutes les couleurs, polices et tailles récurrentes sont stockées dans des **Variables CSS** (dans `:root`) pour faciliter la maintenance et permettre des modifications globales rapides.

### Display : Flex et Grid
La mise en page est construite sans frameworks externes, en s'appuyant exclusivement sur les propriétés CSS modernes :
- **`display: grid`** : Pour les structures bidirectionnelles et les grilles d'éléments (ex: grille des cartes artisans, mise en page globale du footer).
- **`display: flex`** : Pour les alignements fluides et unidirectionnels (ex: barres de navigation, alignement des icônes et du texte).

---

##  3. Développements

*(Cette section est à compléter avec vos détails techniques spécifiques)*

### Technologies utilisées
- HTML5 (Sémantique)
- CSS3 (Variables, Flexbox, Grid, Responsive Design)

### État de l'intégration
- [x] Structure de base du projet.
- [x] Intégration de la navigation et du footer.
- [x] Grille des cartes dynamiques.
- [ ] Section à venir...

### Instructions d'installation locale
1. Cloner le dépôt : `git clone <lien-du-repo>`
2. Se placer sur la branche de développement : `git checkout dev`
3. Ouvrir le fichier `index.html` dans un navigateur.