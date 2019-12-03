---
title: "Interview on adaptive learning"
subtitle: ""
summary: ""
authors: []
tags: ['research', 'machine learning', 'stream learning', 'evolving data streams']
categories: ['research']
date: 2019-10-25
lastmod: 2019-10-25
featured: false
draft: false
---

My interview on the benefits of adaptive learning methods has been published in a white-book by [Quantmetry](https://www.quantmetry.com/).

The white-book, No. 5 "AI en production", is free to download [here](https://www.quantmetry.com/les-livres-blancs/).

---

### Transcript of the interview
(in french)

#### Qu’est-ce qu’une dérive ?

L’apprentissage est souvent considéré comme une tâche statique. Cependant, en conditions réelles, les données évoluent constamment. C’est ce qu’on appelle une dérive conceptuelle. Par exemple, les marchés financiers sont instables : les risques de crédit ne sont pas les mêmes d’une année sur l’autre.
Quelles conséquences pour les modèles classiques ?
Les modèles standards ont toutes les chances d’échouer, car ils ignorent complètement ce phénomène. Souvent, on développe un modèle et, après l’avoir fait fonctionner une fois, on pense que le travail est terminé. En réalité, il faut toujours évaluer la performance du modèle en production au cours du temps et évaluer s’il est sujet à une dérive.

#### Quelles sont les solutions ?

Ce phénomène a été largement étudié dans la littérature sur le stream mining, où plusieurs solutions ont été proposées. Dans ce cadre, les modèles s’adaptent au fur et à mesure. En effet, certaines méthodes permettent de détecter automatiquement les changements dans les données en surveillant la performance des modèles. Elles permettent d’indiquer : "attention, un changement est en train de s’opérer, il faut réagir maintenant". L’idée est ensuite de créer des modèles qui s’adaptent rapidement aux changements. Par exemple, si une dérive est détectée, on peut rejeter un modèle obsolète et déclencher l’apprentissage d’un nouveau modèle.

#### Peut-on utiliser ces techniques quand les données arrivent par cohorte ?

Pas directement, car dans ce cas, il faut attendre entre deux acquisitions successives de données. C’est en effet caractéristique de l’approche statique, car sous l’hypothèse de données identiquement distribuées, il est avantageux d’accumuler autant de données que possible. En stream mining, cette phase d’accumulation n’a pas lieu d’être, il n’y a même pas de problématique de stockage car la donnée est exploitée à la volée. De toute façon, pour être réactif et adaptatif, il vaut mieux attendre le moins longtemps possible. Ceci étant dit, des recherches en cours étudient des systèmes hybrides, où une brique statique et une brique adaptative peuvent collaborer.

#### Quels sont les outils dédiés à l’apprentissage adaptatif ?

Il y a des initiatives comme MOA (Massive Online Analysis), écrit en Java, et scikit-multiflow, écrit en Python. Les deux librairies sont en accès libre et implémentent l’état de l’art des algorithmes adaptatifs en stream mining. Elles ont été développées par des chercheurs mais conçues pour les professionnels. Quelques fournisseurs Cloud proposent également des solutions optimisées pour les flux de données, mais la plupart ignorent le problème de la dérive.

#### L’apprentissage adaptatif est-il crucial pour l’intelligence artificielle en production ?

Dans l’industrie, on ne peut pas toujours reproduire ce qui se fait ailleurs car ce qui fonctionne bien dans un cas peut ne pas fonctionner dans une autre. La clef est vraiment de comprendre en profondeur la donnée, de travailler par itération, d’essayer différentes techniques. La solution est toujours personnalisée et particulière au problème traité. Si la donnée évolue par nature et est produite en masse, alors l’apprentissage adaptatif est en effet très prometteur. Dans ce contexte, il fournit les meilleurs performances et la gestion de ressources informatiques la plus efficace.

#### Pourquoi y a-t-il un tel écart entre les pratiques universitaires et industrielles ?

Les cycles de développement sont relativement différents. En recherche, il est naturel d’aller toujours plus loin, d’expérimenter et d’échouer. L’industrie est plus prudente, et requiert des solutions non seulement efficaces mais également stables, car les enjeux sont bien plus sensibles. L’industrie utilise ce qui marche dans son contexte et l’adapte à son besoin. Ces deux mondes évoluent dans des directions complémentaires. A n’en pas douter, toute collaboration entre universitaires et industriels est bénéfique pour les deux.