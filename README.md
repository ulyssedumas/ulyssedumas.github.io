# Portfolio Personnel - Ulysse Dumas

Bienvenue sur le code source de mon portfolio personnel. Ce site web statique a été conçu pour présenter mon parcours académique, mes passions (photographie, sport, pêche) et mes ambitions en tant que futur ingénieur en Santé Numérique.

## 🎯 Objectif du Projet

L'objectif de ce projet est de concevoir une vitrine web claire, rapide et accessible, reflétant mon identité professionnelle. J'ai porté une attention particulière aux détails de l'interface (UI), à l'expérience utilisateur (UX) et aux performances techniques.

## ✨ Fonctionnalités Principales

* **Mode Sombre / Clair (Dark/Light Mode) :** Intégration d'un thème "Santé Numérique" (bleu médical / turquoise) avec bascule manuelle via un bouton dédié. Le choix de l'utilisateur est mémorisé via le `localStorage`.
* **Accessibilité Visuelle :** Palette de couleurs soigneusement sélectionnée pour garantir un contraste optimal et éviter les pièges visuels pour le daltonisme (évitement des associations rouge/vert critiques).
* **Responsive Design :** Interface fluide et adaptée à tous les écrans (Desktop, Tablette, Mobile). Le menu mobile intègre un défilement horizontal natif (swipe) pour une ergonomie proche des applications mobiles.
* **Animations Dynamiques :**
  * Effet "Machine à écrire" (Typewriter) sur les titres principaux.
  * Apparition fluide des éléments au défilement (Scroll Reveal) gérée de manière performante grâce à l'`IntersectionObserver`.
* **Galerie Interactive :** Visionneuse d'images (Modal) intégrée en JavaScript natif.
* **Performances Optimisées :** Utilisation du format d'image nouvelle génération `.webp`, compression sans perte, et implémentation du chargement différé (`loading="lazy"`) pour un affichage instantané.

## 🛠️ Technologies Utilisées

Ce projet est développé sans framework lourd afin de garantir un contrôle total et une légèreté maximale :

* **HTML5** (Structure sémantique)
* **CSS3** (Variables CSS, Flexbox, CSS Grid, Media Queries, Transitions)
* **JavaScript (Vanilla)** (Manipulation du DOM, Intersection Observer, LocalStorage)
* **FontAwesome** (Bibliothèque d'icônes vectorielles)

## 📁 Architecture du Projet

```text
/
├── index.html       # Page d'accueil
├── parcours.html    # Mon parcours académique et professionnel
├── passions.html    # Mes centres d'intérêt et galerie photo
├── avenir.html      # Mes projets futurs en Santé Numérique
├── style.css        # Feuille de style globale et variables de thèmes
├── images/          # Dossier contenant toutes les ressources visuelles (.webp)
└── README.md        # Documentation du projet