# EcoArt
EcoArt est un projet d'intégration web complet de 5 pages à réaliser en équipe.  Nous devons analyser les wireframes fournies, les transformer en maquettes avec prototype interactif, puis développer le site web responsive en CSS Pur avec (Grid, Flexbox, Variables CSS, Mobile-First).


# Projet EcoArt

Bienvenue sur le projet EcoArt. Vous trouverez ci-dessous les liens vers nos maquettes design.

##  Maquette Figma - Responsive
Voici la version adaptée pour les écrans de tablette :
- [Voir la maquette Tablette](https://www.figma.com/design/eJPFw2QBbBnVMgmPvTKv0B/EcoArt-Tabel-Version?node-id=15-6303&t=DdnXXq7KX3uycotP-1)

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