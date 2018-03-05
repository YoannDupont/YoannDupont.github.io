---
layout: default_fr
---

La thèse sera bientôt rendue disponible sur [TEL archives](https://tel.archives-ouvertes.fr/).

# Ma thèse : "La structuration dans les entités nommées"

Cette thèse CIFRE a été réalisée en partenariat avec l'entreprise Expert System France (ex TEMIS).

## Jury de thèse

- [Isabelle Tellier](http://lattice.cnrs.fr/sites/itellier/) (directrice de thèse)
- [Marco Dinarelli](http://marcodinarelli.it/) (co-encadrant)
- Christian Lautier (co-encadrant)
- [Agata Savary](http://www.info.univ-tours.fr/~savary/) (rapporteure)
- [François Yvon](https://perso.limsi.fr/yvon/mysite/mysite.php) (rapporteur)
- [Frédéric Landragin](http://fred.landragin.free.fr) (examinateur)
- [Pascale Sébillot](http://www.irisa.fr/texmex/people/sebillot/index_fr.php) (examinatrice)
- [Patrick Watrin](https://uclouvain.be/fr/repertoires/patrick.watrin) (examinateur)

## Soutenance

Thèse soutenue le 23 Novembre 2017 à 14h. [Avis de soutenance](http://www.univ-paris3.fr/soutenance-de-these-de-m-yoann-dupont-461858.kjsp)

## Résumé

La reconnaissance des entités nommées est une discipline cruciale du domaine du TAL. Elle sert à l'extraction de relations entre entités nommées, ce qui permet la construction d'une base de connaissances [(Surdeanu and Ji, 2014)](https://pdfs.semanticscholar.org/6d54/cce97861b9d38c700e1282d34d5236bf3bdb.pdf), le résumé automatique [(Nobata et al., 2002)](https://pdfs.semanticscholar.org/c500/40ac812c3f3de0cf37802ff87de2dce87821.pdf), etc. Nous nous intéressons ici aux phénomènes de structurations qui les entourent.

Nous distinguons tout d'abord deux types d'éléments structurels dans une entité nommée. Les premiers sont des sous-chaînes récurrentes, que nous appellerons les _affixes caractéristiques_ d'une entité nommée. Le second type d'éléments est les tokens ayant un fort pouvoir discriminant, appelés des _tokens déclencheurs_. Nous détaillerons l'algorithme que nous avons mis en place pour extraire les affixes caractéristiques, que nous comparerons à Morfessor [(Creutz and Lagus, 2005b)](https://pdfs.semanticscholar.org/2d6a/97f83bb8207ea9d88118618ed3ab52054a88.pdf). Nous appliquerons ensuite notre méthode pour extraire les tokens déclencheurs, utilisés pour l'extraction d'entités nommées du français et d'adresses postales.

Une autre forme de structuration pour les entités nommées est de nature syntaxique, d'imbrications ou arborée. Pour identifier automatiquement cette structuration, nous proposons un type de cascade d'étiqueteurs linéaires qui n'avait jusqu'à présent jamais été utilisé pour la reconnaissance d'entités nommées. Elles généralisent les approches précédentes qui sont capables de reconnaître uniquement des entités de profondeur limitée ou qui ne peuvent pas modéliser certaines particularités des entités nommées structurées.

Tout au long de cette thèse, nous comparons deux méthodes par apprentissage automatique, à savoir les CRF et les réseaux de neurones, dont nous présenterons les avantages et inconvénients.

### Mots-clés

- reconnaissance des entités nommées
- entités nommées structurées
- apprentissage automatique
- champs aléatoires conditionnels
- réseaux de neurones
