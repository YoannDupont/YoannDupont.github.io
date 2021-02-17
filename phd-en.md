---
layout: default
---

[See this page in French](phd-fr)

This thesis is available (in French) on [TEL archives](https://tel.archives-ouvertes.fr/tel-01772268/document).

# My PhD Thesis: "Structuration in Named Entities"

This PhD thesis was realised in collaboration with the company Expert System France (ex TEMIS).

## Thesis examiners

- [Isabelle Tellier](http://lattice.cnrs.fr/sites/itellier/) (supervisor)
- [Marco Dinarelli](http://marcodinarelli.it/) (co-tutor)
- Christian Lautier (co-tutor)
- [Agata Savary](http://www.info.univ-tours.fr/~savary/) (reporter)
- [François Yvon](https://perso.limsi.fr/yvon/mysite/mysite.php) (reporter)
- [Frédéric Landragin](http://fred.landragin.free.fr) (examiner)
- [Pascale Sébillot](http://www.irisa.fr/texmex/people/sebillot/index_fr.php) (examiner)
- [Patrick Watrin](https://uclouvain.be/fr/repertoires/patrick.watrin) (examiner)

## Defence

PhD defended on 2017 November the 23rd at 14h. [defence notice (french)](http://www.univ-paris3.fr/soutenance-de-these-de-m-yoann-dupont-461858.kjsp)

## Abstract

Named entity recognition is a crucial discipline of NLP. It is used to extract relations between named entities, which allows the construction of knowledge bases [(Surdeanu and Ji, 2014)](https://pdfs.semanticscholar.org/6d54/cce97861b9d38c700e1282d34d5236bf3bdb.pdf), automatic summary [(Nobata et al., 2002)](https://pdfs.semanticscholar.org/c500/40ac812c3f3de0cf37802ff87de2dce87821.pdf) and so on. Our interest in this thesis revolves around structuring phenomena that surround them.

We distinguish here two kinds of structural elements in named entities. The first one are récurrent substrings, that we will call the \emph{characteristic affixes} of a named entity. The second type of element is tokens with a good discriminative power, which we call \emph{trigger tokens} of named entities. We will explain here the algorithm we provided to extract such affixes, which we will compare to Morfessor [(Creutz and Lagus, 2005b)](https://pdfs.semanticscholar.org/2d6a/97f83bb8207ea9d88118618ed3ab52054a88.pdf). We will then apply the same algorithm to extract trigger tokens, which we will use for French named entity recognition and postal address extraction.

Another form of structuring for named entities is of a syntactic nature, where entities typically have a tree structure. We propose a novel kind of linear tagger cascade which has not been used before for structured named entity recognition, generalising other previous methods that are only able to recognise named entities of a fixed depth or unable to model certain characteristics of the structure. Ours, however, can do both.

Throughout this thesis, we compare two machine learning methods, CRFs and neural networks, for which we will compare respective advantages and drawbacks.

### Keywords

- named entity recognition
- structured named entities
- machine learning
- conditional random fields
- neural networks
