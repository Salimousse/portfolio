---
title: Festival CaleSons
publishDate: 2026-05-06 00:00:00
img: /assets/cale-sons-logo.png
img_alt: Logo du Festival CaleSons
description: |
  Plateforme complète de gestion, organisation et billetterie pour festivals et événements culturels développée en Laravel.
tags:
  - Laravel
  - PHP
  - Stripe
  - TailwindCSS
---

Ce projet représente AP4_WEB.

[Voir le projet sur GitHub](https://github.com/Salimousse/AP4_WEB)

# Plateforme de Gestion de Festival & Événements (AP4 Web)

Ce projet est une application web complète développée avec **Laravel** dédiée à la gestion, l'organisation et la billetterie de festivals et d'événements culturels (concerts, conférences, ateliers).

## Fonctionnalités Principales

### Billetterie & Réservations
- **Système de Réservation** : Réservation de billets pour les différentes manifestations.
- **Paiements en ligne sécurisés** : Intégration de l'API **Stripe** pour la gestion des transactions.
- **Génération de QR Codes** : Création de QR Codes pour la validation électronique des billets.
- **Gestion des Types de Paiements** : Support de multiples méthodes de paiement.

### Gestion des Événements
- **Festivals et Manifestations** : Création et gestion complète de festivals.
- **Multi-formats** : Prise en charge de divers types d'événements tels que les **Concerts**, **Conférences** et **Ateliers**.
- **Gestion des Lieux** : Attribution de salles et lieux spécifiques pour chaque événement.
- **Domaines & Spécialités** : Catégorisation des événements par domaine.

### Intervenants & Artistes
- **Gestion des Profils** : Suivi des artistes et des intervenants.
- **Affectation aux événements** : Gestion de qui *anime*, *présente* ou *produit* lors d'une manifestation.

### Chatbot & Messagerie en Temps Réel
- **Messagerie Instantanée** : Système de chat en temps réel (alimenté par **Reverb / Pusher**).
- **Service Client Automatisé (Chatbot)** : Intégration d'un assistant virtuel.
- **Détection d'Escalade** : Système intelligent capable d'analyser la conversation pour rediriger un utilisateur vers un administrateur humain si besoin.

### Sponsoring
- **Gestion des Sponsors** : Mise en valeur des partenaires commerciaux du festival.
- **Niveaux de Sponsoring** : Hiérarchisation des sponsors selon leur contribution financière.

### Utilisateurs & Administration
- **Rôles & Accès** : Support des clients, administrateurs et intervenants.
- **Avis et Retours** : Système permettant aux clients de laisser des avis sur les événements.

---

## Stack Technique

- **Framework Backend** : Laravel (PHP)
- **Frontend** : Blade, HTML/CSS/JS compilés via **Vite**
- **Design Web** : **Tailwind CSS**
- **Websockets** : Laravel Reverb / Pusher pour le temps réel
- **Paiements** : Stripe API
