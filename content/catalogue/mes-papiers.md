+++
title = 'Mes Papiers'
draft = false
+++

![Logo Mes Papiers](/images/mes_papiers.jpg)

## Description

“Mes papiers” est une application développée par la Métropole de Lyon afin de **faciliter les démarches administratives** (RSA, CAF, etc.) pour les usagers ainsi que les agents.

L’application permet de rassembler de nombreux documents administratifs (carte d’identité, attestations, carte grise, facture énergie, etc.) dans un seul endroit et de les partager facilement à des tiers.

L’objectif est ainsi de faciliter d’un côté le stockage et la recherche ultérieure de ces documents, et d’un autre côté l’échange d’informations avec des contacts privés ou des travailleurs sociaux dans le cadre de demandes de prestation.

## Infrastructure self data utilisée

“Mes papiers” est une application qui s'appuie sur l'espace de stockage numérique **Cozy Cloud**.

L'utilisateur doit se créer un compte soit sur le domaine cozy classique (**mycozy.cloud**), soit sur le domaine cozy fourni par la Métropole de Lyon (**cozygrandlyon.cloud**).
Une fois connecté a son compte, soit par le navigateur web, soit par l'application mobile Cozy, l’utilisateur peut ajouter gratuitement l'application _Mes Papiers_ dans son _cozy_.

Cette application est une **vue augmentée** du système de gestion de fichiers de _cozy_.

Elle permet à son utilisateur à d’importer des photos ou scans de ses documents, en les catégorisant dès leur envoi sur l’espace de stockage (carte d'identité, carte grise, facture d'énergie, etc…), et en y ajoutant des méta-données (le numéro de la carte d'identité, sa date limite de validité, le numéro d'allocataire) pour mieux les retrouver et les partager plus tard.

De plus, grâce à un système de connecteurs avec des services extérieurs, “Mes Papiers” permet de se connecter une fois à des services extérieurs comme les impôts,
la Caisse d'Allocations Familiales, le fournisseur d'accès à internet, etc… pour aller récupérer par la suite automatiquement différents documents directement à la source.

Les documents sont transférés et stockés dans une arborescence de dossiers créé automatiquement par l'application dans l'espace de stockage _Cozy_, et sont cherchables et partageables facilement avec des tiers.

La feuille de route développement prévoit un mode d’accès sécurisé qui permettra de donner lors d'un rendez-vous accès à l'ensemble de ses documents (hors mots de passe) à un professionnel identifié, pour faciliter les opérations d’assistance de travailleurs sociaux par exemple.

## Méthode de déploiement

Si le projet est une commande de la Métropole de Lyon à Cozy, l'application produite est un commun numérique qui est accessibles à tous les utilisateurs d’espaces numériques Cozy, qu'ils soient utilisateurs gratuits ou payants de l'offre de Cozy, ou utilisateur des espaces numériques cozy fournis par la Métropole de Lyon aux habitants du territoire.

## Liens utiles

- [Ressourcerie en ligne du projet](https://service-numerique-metropole.notion.site/Ressourcerie-du-projet-Mes-Papiers-493186d3b7b844739322310d703617b3)
- [Code source (sur github)](https://github.com/cozy/mespapiers)


## Parties prenantes

- [Métropole de Lyon](https://www.grandlyon.com/)
- [Cozy Cloud](https://cozy.io/fr/)
- [Lyon Métropole Habitat](https://www.lmhabitat.fr/)
- [ATD Quart Monde](https://www.atd-quartmonde.fr/)
- Centre sociaux :
  - [Artag](https://artag.centres-sociaux.fr/),
  - [Gisèle Halimi et Mermoz](https://www.cshalimimermoz.fr/)
  - [Quartier Vitalité](https://www.centresocialquartiervitalite.fr/)
- [Union Départementale des Centres Communaux d'Action Sociale du Rhône et de la Métropole de Lyon UDCCAS 69](https://udccas69.org/)
- Communes :
  - [Lyon](https://www.lyon.fr/)
  - [Vaulx-en-Velin](https://vaulx-en-velin.net/)

## Contacts

Gestion de produit : Lucie Billaud, Chef de projet Self-Data à la Métropole de Lyon
Référent métier : Antoine Louvet, Chef de projet Inclusion Numérique à la Métropole de Lyon
