
<div align="center">

 <img width="1053" height="1008" alt="logo" src="https://github.com/user-attachments/assets/c1167e18-7783-4645-aeb2-97bb6e36a6d0" />


# FITAHIANTSOA

### Entreprise & Fournisseur — Madagascar

**FITAHIANTSOA** est un projet de plateforme numérique destinée à faciliter la mise en relation entre fournisseurs, clients et différents acteurs liés au commerce et à la logistique.

[**Voir le site en ligne**](https://sergioolivier.github.io/SITE_FITAHIANTSOA/)

</div>

<br>

<img src="assets/banner.jpg" alt="FITAHIANTSOA" width="100%">

<br>

## À propos du projet

**FITAHIANTSOA** est un projet numérique développé autour d'une entreprise malgache spécialisée dans l'importation et la distribution de matériel agricole.

Le projet a pour objectif de faire évoluer cette activité vers un environnement numérique permettant de présenter des produits, gérer des commandes et simuler les interactions entre les différents acteurs de l'entreprise.

Le site présente notamment des produits agricoles tels que des motoculteurs, tracteurs, motopompes et décortiqueuses de riz, tout en intégrant progressivement d'autres secteurs :

* Agriculture
* Artisanat malgache
* Tourisme durable
* Électronique
* Mode
* Matériel médical

Le projet constitue actuellement un **prototype fonctionnel à des fins de démonstration et de présentation**.

## Objectifs

Le projet vise à concevoir une interface numérique permettant de :

* présenter les produits et leurs caractéristiques ;
* faciliter la recherche de produits ;
* simuler un parcours d'achat ;
* suivre les commandes ;
* organiser les différents espaces utilisateurs ;
* présenter les interactions entre fournisseurs, clients et partenaires ;
* proposer une architecture pouvant évoluer vers une application complète.

## Fonctionnalités

### Catalogue et recherche

* Catalogue de produits
* Recherche de produits
* Filtrage par catégorie
* Filtrage par prix
* Filtrage par note
* Informations sur l'origine des produits
* Fiches produits détaillées
* Galerie d'images
* Caractéristiques techniques
* Avis
* QR code produit

### Panier et commandes

* Ajout de produits au panier
* Modification des quantités
* Récapitulatif de commande
* Simulation du processus de commande
* Adresse de livraison
* Mode de paiement
* Confirmation de commande
* Suivi de commande
* Timeline de livraison

### Espace client

* Gestion du compte
* Historique des commandes
* Produits favoris
* Consultation des commandes
* Suivi des livraisons

### Espace fournisseur

* Gestion des produits
* Ajout de produits
* Suivi des ventes
* Consultation des revenus
* Gestion du catalogue

### Espace employé

* Validation des produits
* Gestion des commandes
* Gestion des réclamations
* Suivi des opérations

### Espace administrateur

* Tableau de bord
* Statistiques
* Gestion des utilisateurs
* Gestion des produits
* Suivi financier
* Gestion marketing

### Espace partenaire logistique

* Gestion des missions de livraison
* Suivi des livraisons
* Gestion des opérations logistiques

## Produits présentés

| Produit                                | Description                                                           |
| -------------------------------------- | --------------------------------------------------------------------- |
| **Motoculteur diesel Changfa 12 CV**   | Équipé d'une fraise rotative pour les travaux de labour et de hersage |
| **Motoculteur diesel Hong Yuan 31 CV** | Modèle à injection directe destiné aux grandes parcelles              |
| **Tracteur agricole 4 roues**          | Destiné au labour, au transport et aux travaux agricoles lourds       |
| **Motopompe diesel NS-150**            | Utilisée pour l'irrigation et le pompage d'eau                        |
| **Décortiqueuse de riz**               | Destinée aux coopératives et petites unités de transformation         |

## Technologies

Le prototype actuel repose principalement sur :

* **HTML5** — structure de l'application
* **CSS3** — mise en page et responsive design
* **JavaScript** — logique et interactions
* **React 18** — composants et interface utilisateur
* **Lucide Icons** — icônes de l'interface
* **GitHub Pages** — hébergement du prototype

Le prototype est conçu pour fonctionner sans étape de build complexe.

Une partie importante de l'interface et des données de démonstration est regroupée dans le fichier `index.html`, ce qui permet de déployer facilement le prototype sur GitHub Pages.

## Structure du projet

```text
SITE_FITAHIANTSOA/
│
├── index.html
│
├── assets/
│   ├── logo.jpg
│   └── banner.jpg
│
└── README.md
```

### Description

```text
index.html
→ Interface principale du prototype, composants et données de démonstration.

assets/
→ Logo et ressources graphiques utilisées par le projet.

README.md
→ Documentation du projet.
```

## Installation et utilisation

Aucune installation particulière n'est nécessaire pour consulter le prototype.

### Méthode 1 — Site en ligne

Le prototype est accessible directement depuis GitHub Pages :

[**FITAHIANTSOA — Site en ligne**](https://sergioolivier.github.io/SITE_FITAHIANTSOA/)

### Méthode 2 — Utilisation locale

Cloner le dépôt :

```bash
git clone https://github.com/sergioolivier/SITE_FITAHIANTSOA.git
```

Accéder au dossier :

```bash
cd SITE_FITAHIANTSOA
```

Puis ouvrir `index.html` dans un navigateur.

Il est également possible d'utiliser une extension comme **Live Server** avec Visual Studio Code pour lancer le projet localement.

## Déploiement

Le prototype est hébergé avec **GitHub Pages**.

Chaque modification du projet peut être versionnée avec Git puis publiée sur le dépôt GitHub.

Le site de démonstration est disponible à l'adresse :

https://sergioolivier.github.io/SITE_FITAHIANTSOA/

## Architecture actuelle

Le projet est actuellement conçu comme un **prototype front-end**.

Les données utilisées dans l'interface sont des données de démonstration. Les fonctionnalités telles que le paiement réel, l'authentification sécurisée, la gestion réelle des stocks, la base de données et la livraison réelle nécessiteraient une infrastructure back-end et des services externes.

L'architecture pourra évoluer vers une application complète comprenant notamment :

```text
Interface utilisateur
        │
        ▼
Application Front-End
        │
        ▼
API / Back-End
        │
        ├── Base de données
        ├── Authentification
        ├── Gestion des commandes
        ├── Gestion des produits
        ├── Paiement
        └── Logistique
```

## Statut du projet

**Statut : Prototype fonctionnel**

Le projet est actuellement destiné à la démonstration de l'interface, de l'expérience utilisateur et de la conception générale de l'application.

Les données présentées sont fictives ou utilisées à titre de démonstration.

Les fonctionnalités professionnelles présentées dans les différents espaces sont des simulations d'interface et ne constituent pas encore un système de production complet.

## Évolutions envisagées

Les prochaines étapes pourraient inclure :

* création d'un véritable back-end ;
* mise en place d'une base de données ;
* authentification des utilisateurs ;
* gestion réelle des comptes et des rôles ;
* gestion des stocks ;
* système de paiement sécurisé ;
* système réel de commandes ;
* API pour les fournisseurs et partenaires ;
* suivi logistique en temps réel ;
* application mobile ;
* système de notifications ;
* sécurisation des données ;
* déploiement d'une infrastructure complète.

## Captures d'écran

Le dossier contient plusieurs captures d'écran présentant les différentes interfaces du prototype, notamment :

* page d'accueil ;
* catalogue ;
* fiches produits ;
* panier ;
* commande ;
* suivi de livraison ;
* espace client ;
* espace fournisseur ;
* espace employé ;
* espace administrateur ;
* espace partenaire logistique.

## Auteur

**Sergio Olivier**

Projet réalisé dans le cadre du développement et de la conception d'une solution numérique pour **FITAHIANTSOA**, Madagascar.

## Licence

Tous droits réservés — FITAHIANTSOA.

---

<div align="center">

**FITAHIANTSOA — Ensemble pour un avenir durable**

</div>
