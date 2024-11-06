# Bonjour

## Introduction



### Principes <a href="#principes" id="principes"></a>

Slate tente de répondre à la question "[Pourquoi ?](https://app.gitbook-staging.com/o/IB7NBledmg4rv6DqKKwF/s/QQfP8VgjleNAJQfwLg7F/#why)" avec quelques principes :

1. **Plugins de premier ordre.** La partie la plus importante de Slate est que les plugins sont des entités de premier ordre. Cela signifie que vous pouvez _complètement_ personnaliser l'expérience d'édition pour créer des éditeurs complexes comme ceux de Medium ou Dropbox, sans avoir à lutter contre les hypothèses de la bibliothèque.
2. **Noyau sans schéma.** La logique centrale de Slate suppose très peu de choses sur le schéma des données que vous allez éditer, ce qui signifie qu’il n’y a pas d’hypothèses intégrées dans la bibliothèque qui vous gêneront lorsque vous devrez aller au-delà des cas d'utilisation les plus basiques.
3. **Modèle de document imbriqué.** Le modèle de document utilisé pour Slate est un arbre imbriqué et récursif, tout comme le DOM lui-même. Cela signifie que la création de composants complexes comme des tableaux ou des citations imbriquées est possible pour des cas d'utilisation avancés. Mais il est également facile de le garder simple en n'utilisant qu'un seul niveau de hiérarchie.
4. **Parallèle au DOM.** Le modèle de données de Slate est basé sur le DOM : le document est un arbre imbriqué, il utilise des sélections et des plages, et il expose tous les gestionnaires d'événements standard. Cela signifie que des comportements avancés comme les tableaux ou les citations imbriquées sont possibles. Pratiquement tout ce que vous pouvez faire dans le DOM, vous pouvez le faire dans Slate.
5. **Commandes intuitives.** Les documents Slate sont édités à l'aide de "commandes", conçues pour être de haut niveau et extrêmement intuitives à écrire et à lire, de sorte que la fonctionnalité personnalisée soit aussi expressive que possible. Cela accroît considérablement votre capacité à raisonner sur votre code.
6. **Modèle de données prêt pour la collaboration.** Le modèle de données utilisé par Slate—en particulier la manière dont les opérations sont appliquées au document—a été conçu pour permettre l’édition collaborative, vous n’aurez donc pas besoin de repenser tout si vous décidez de rendre votre éditeur collaboratif.
7. **Limites claires du "noyau".** Avec une architecture centrée sur les plugins et un noyau sans schéma, il devient beaucoup plus clair où se trouve la frontière entre "noyau" et "personnalisé", ce qui signifie que l'expérience de base ne se retrouve pas ralentie par des cas particuliers.



