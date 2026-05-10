---
title: Application Mobile CDS 49 
publishDate: 2026-05-04 00:00:00
img: /assets/logo_cds49.jpeg
img_alt: Logo de l'auto-école CDS 49
description: |
  Application mobile de révision du Code de la Route développée avec Flutter pour l'auto-école CDS 49.
tags:
  - Mobile
  - Flutter
  - API REST
---

## Contexte & Objectif

L'auto-école **CDS 49** souhaitait moderniser son offre. J'ai eu la charge de développer leur application mobile pour offrir aux élèves une plateforme interactive d'entraînement au Code de la Route.

[Voir le projet sur GitHub](https://github.com/Salimousse/AP3_mobile)

## Technologies Utilisées

*   **Front-end Mobile :** Flutter (Dart)
*   **Back-end :** API REST en PHP
*   **Base de données :** MySQL

## Fonctionnalités Clés

### 1. Entraînement Interactif (Quiz)
Fonctionnalité centrale de l'application :
*   Sélection de la catégorie du quiz.
*   Questions générées aléatoirement via l'API.
*   Chronomètre intégré pour chaque question.
*   Enregistrement du score à la fin de la série pour le suivi de la progression.



### 2. Authentification sécurisée
Accès réservé aux élèves de l'auto-école. L'application vérifie les identifiants auprès de l'API (requêtes HTTP) sans jamais interroger la base de données en direct, garantissant ainsi la sécurité.

### 3. Informations pratiques
Consultation rapide des coordonnées, horaires, avec des interactions natives (appel direct au clic sur le numéro).

