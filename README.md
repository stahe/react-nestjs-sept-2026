# RdvMedecins - un exemple de client / serveur avec NestJS et React

Ce dépôt accompagne un cours consacré à la reconstruction, avec des outils actuels, d'une application client/serveur de prise de rendez-vous médicaux (`RdvMedecins`). Il ne contient que ce README : le cours complet est publié en ligne.

## 📖 Lire le cours

**[https://stahe.github.io/react-nestjs-sept-2026](https://stahe.github.io/react-nestjs-sept-2026)**

## À propos

Ce document transpose vers des technologies actuelles un cours original de 2014 (*Un exemple de client / serveur - AngularJS 1.x / Spring 4*) :

- le serveur, écrit en Java avec Spring MVC, est remplacé par un serveur **NestJS** (TypeScript) ;
- le client **AngularJS 1.x** est remplacé par un client **React** (composants fonctionnels, hooks) ;
- le cœur fonctionnel et la base de données restent inchangés dans leur principe, à l'ajout près d'une authentification par rôles (JWT) absente de l'original.

Le cours a été rédigé avec l'assistance de l'IA Claude (Anthropic), qui a produit l'essentiel des codes et des explications ; l'auteur a testé et validé l'ensemble en suivant le document généré.

## Contenu du cours

1. **Introduction** - objectifs, prérequis, architecture générale de l'application
2. **Chapitre 1** - Mise en place de l'environnement de travail
3. **Chapitre 2** - Introduction à NestJS
4. **Chapitre 3** - Le serveur NestJS de l'application RdvMedecins
5. **Chapitre 4** - Introduction à React
6. **Chapitre 5** - Le client React de l'application RdvMedecins
7. **Chapitre 6** - Conclusion et étapes suivantes

## Technologies abordées

- **Serveur** : NestJS, TypeORM, MySQL, authentification JWT (`@nestjs/passport`, `@nestjs/jwt`), contrôle d'accès par rôles
- **Client** : React 19, Vite, TypeScript, hooks, i18next (internationalisation français/anglais), Bootstrap

## Prérequis

Aucune connaissance préalable de NestJS ou de React n'est nécessaire. Des bases en JavaScript, en HTTP et en ligne de commande suffisent pour aborder le cours dans de bonnes conditions.

## Auteurs

IA Claude (principalement) et Serge Tahé (tests code et relecture cours)
