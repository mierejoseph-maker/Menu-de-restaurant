# Menu-de-restaurant
Le gourmet du getho

Site vitrine en *HTML pur* présentant le menu complet d'un restaurant congolais fictif, "Le gourmet du getho". Le projet met l'accent sur une sémantique HTML5 avancée.

## Aperçu

Le fichier restaurant-index.html est une page unique et autonome  qui présente :

- 33 plats répartis en 4 catégories
- Une section "Spécial du jour"
- Un tableau comparatif des prix
- Les horaires d'ouverture
- Un formulaire de réservation
- Les coordonnées du restaurant

## Structure du contenu

| Section | Ancre | Description |
|---|---|---|
| Spécial du jour | #special-du-jour | Plat mis en avant du jour, avec prix barré |
| Entrées | #entrees | 8 entrées traditionnelles |
| Plats principaux | #plats | 12 plats principaux |
| Desserts | #desserts | 6 desserts |
| Boissons | #boissons | 7 boissons |
| Tableau des prix | #comparatif-prix | Comparatif min/max/moyen par catégorie |
| Horaires | #horaires | Horaires d'ouverture (liste de définition) |
| Réservation | #reservation | Formulaire de réservation en ligne |
| Contact | #contact | Coordonnées, réseaux sociaux, accès |

Chaque plat est présenté sous forme d'<article> contenant : nom, image, description, prix et liste d'ingrédients.

## Choix techniques

- *Sémantique HTML5* : header, nav, main, section, article, figure/figcaption, dl, table, form, fieldset, address, footer
- *Accessibilité (ARIA)* :
  - Lien d'évitement (skip-link) vers le contenu principal
  - aria-label sur la navigation principale
  - aria-labelledby pour associer chaque section à son titre
  - aria-current="page" pour l'élément de navigation actif
  - aria-required sur les champs obligatoires du formulaire
  - Attributs alt descriptifs sur toutes les images
  - Focus visible personnalisé au clavier
- *Formulaire de réservation* : chaque champ possède un label associé via for/id, regroupé en fieldset/legend (coordonnées / détails de réservation)
- *Images* : générées via google
- ## Comment consulter le projet

1. Télécharger restaurant-index.html
2. L'ouvrir directement dans un navigateur (aucun serveur requis)


1. Télécharger menu-restaurant-congolais.html
2. L'ouvrir directement dans un navigateur (aucun serveur requis)
