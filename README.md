# Introduction au langage Dart par l'exemple

> ⚠️ **Ce dépôt n'est pas un projet logiciel.** Il n'y a ici ni application à installer, ni
> package à publier, ni issues de code à corriger : c'est le **support d'un cours**, rédigé
> pour des étudiants découvrant le langage Dart.

## 📖 Lire le cours

Le cours se lit en ligne, à cette adresse :

**👉 [https://stahe.github.io/dart-sept-2026/](https://stahe.github.io/dart-sept-2026/)**

Aucune installation n'est nécessaire pour le lire : un simple navigateur suffit.

## 🎯 À qui s'adresse ce cours ?

Ce cours s'adresse à des étudiants qui n'ont **aucune connaissance préalable** du langage
Dart. Il est conçu sur le même principe que le cours *Introduction au langage TypeScript et
au framework NestJS* : apprendre un langage à travers une série de petits scripts autonomes,
commentés ligne à ligne, plutôt qu'à travers un exposé théorique de sa grammaire. La
progression suit d'ailleurs celle du cours TypeScript pas à pas, un script Dart en face de
chaque script TypeScript, pour permettre de comparer directement comment les deux langages
répondent au même besoin.

## 📚 Plan du cours

Le cours est organisé en grandes parties :

1. **Installation de l'environnement de travail** — vérification des outils, mise en place
   du projet VS Code, premier script, analyse statique, linter, extension Dart.
2. **Les fondamentaux de Dart** — les bases du langage, les tableaux, les objets, les
   chaînes de caractères, les expressions régulières, les fonctions, les erreurs et
   exceptions, les modules, la programmation événementielle et les fonctions asynchrones,
   les classes, et les nouveautés de Dart 3.x (records, patterns, classes scellées).
3. **Installation d'un serveur NestJS** — le serveur de calcul de l'impôt sur le revenu,
   repris tel quel du cours TypeScript : il sert de cible réelle pour tester les fonctions
   HTTP de Dart, exactement comme il sert de cible aux clients HTTP du cours d'origine. (Les
   chapitres qui enseignent NestJS lui-même ne sont volontairement pas repris ici : une
   question sans rapport direct avec l'apprentissage du langage Dart.)
4. **Les fonctions HTTP de Dart et les clients du service de calcul de l'impôt** — quatre
   variantes de client pour un même serveur : script CLI simple, couches DAO/métier
   séparées, projet compilé, puis application web complète avec interface HTML.
5. **L'accès aux bases de données** — le pilote MySQL natif, puis un « ORM léger » écrit à
   la main, faute d'équivalent mûr de TypeORM ou Prisma pour Dart.

## ✍️ Auteur

**L'IA Claude d'Anthropic**

## ✍️ Réviseur
**Serge TAHE** [https://stahe.github.io](https://stahe.github.io)
