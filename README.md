# Projet de Gestion des Produits et Fournisseurs

Ce projet est une application web de gestion des produits et des fournisseurs. Il permet de réaliser les opérations CRUD (Créer, Lire, Mettre à jour et Supprimer) sur des produits et des fournisseurs à partir de pages web interactives.

## Fonctionnalités

- **Gestion des Produits** : Ajouter, modifier, supprimer et lister les produits.
- **Gestion des Fournisseurs** : Ajouter, modifier, supprimer et afficher les détails des fournisseurs.
- **Lien Produit-Fournisseur** : Associer chaque produit à un fournisseur spécifique.

## Technologies utilisées

- **Java** (Spring Boot, Hibernate)
- **Thymeleaf** pour les pages HTML dynamiques
- **MySQL** pour la base de données
- **Maven** pour la gestion des dépendances



## Structure du projet

- `entities` : contient les entités **Produit** et **Fournisseur**.
- `repositories` : contient les interfaces pour accéder aux données des entités.
- `web` : contient les contrôleurs pour gérer les requêtes HTTP.
- `resources/templates` : contient les fichiers HTML pour les pages de l'application (Thymeleaf).

## Instructions d'utilisation

### Ajouter un Produit

1. Accédez à la page d'ajout de produit via `/produits`.
2. Remplissez le formulaire avec les informations du produit et sélectionnez un fournisseur.
3. Cliquez sur "Ajouter" pour enregistrer le produit.

### Modifier un Produit

1. Accédez à la liste des produits via `/produits`.
2. Cliquez sur "Modifier" pour l'élément que vous souhaitez mettre à jour.
3. Modifiez les informations souhaitées et cliquez sur "Modifier" pour enregistrer les changements.

### Supprimer un Produit

1. Accédez à la liste des produits via `/produits`.
2. Cliquez sur "Supprimer" pour l'élément que vous souhaitez supprimer.

## Démos en vidéo

> Front-end



https://github.com/user-attachments/assets/3474cba2-57a7-4e3c-9a59-bc4f2a70c6b2

>Back-end



https://github.com/user-attachments/assets/2fb99e35-4c8a-45f1-b84f-910813ef6d90



