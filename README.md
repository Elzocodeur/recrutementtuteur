# Plateforme de recrutement des tuteurs – UN-CHK (frontend)

Application web de gestion des candidatures de tuteurs pour l'Université Numérique Cheikh Hamidou Kane (UN-CHK). Elle automatise le dépôt et le suivi des candidatures, avec un espace pour les candidats et un espace d'administration. Projet pédagogique réalisé en Angular, avec un backend Spring Boot.

## Fonctionnalités

- Page d'accueil présentant les offres de recrutement
- Authentification (inscription, connexion) et routes protégées
- Espace candidat : dépôt de candidature, suivi de ses candidatures
- Espace d'administration : consultation et traitement des candidatures

## Stack technique

- Angular 18, TypeScript, Tailwind CSS, RxJS, SweetAlert2
- Backend Spring Boot (API REST) déployé sur Render
- Frontend déployé sur Vercel

## Lancer le projet

Prérequis : Node.js 18+ et Angular CLI.

```bash
npm install
ng serve
```

L'application est disponible sur http://localhost:4200/. L'URL de l'API se configure dans `src/environments/`.

Build de production :

```bash
ng build
```

## Auteur

Elimane Gning – [LinkedIn](https://linkedin.com/in/elimane-gning)
