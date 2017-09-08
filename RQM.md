<!-- Use external markdown resource, separate slides by three newlines; vertical slides by two newlines ->
<section data-markdown="RQM.md" data-separator="^\n\n\n" data-separator-vertical="^\n\n"></section>

<!- Guillevic -->

## Guillevic
# _Carnac_
###### un projet [freecodecamp.org](https://freecodecamp.org) <br>dans le cadre de la formation Simplon-co / EMG2017



### Un programme de formation
### aux bases du 
### développement web
découvrir et aborder les technologies <br>et les outils
du développement web 'Front End'<br>

* html<!-- .element: class="fragment" data-fragment-index="1" -->  
* css<!-- .element: class="fragment" data-fragment-index="2" -->
* js<!-- .element: class="fragment" data-fragment-index="3" -->


### LES RESSOURCES MISES EN OEUVRE :
* openclassrooms.com
* freecodecamp.org
* ...<!-- .element: class="fragment" data-fragment-index="1" -->
* un bon brin de curiosité et d'astuce<!-- .element: class="fragment" data-fragment-index="2" -->



#### Premier exercice dans la série des 
## 'Intermediate Development Projects'
#### du programme freecodecamp.org.


### le sujet
Après une introduction succincte aux fonctionnalités asynchrones du langage JavaScript (AJAX), composer une page présentant aléatoirement des citations fournies sous la forme d'un fichier _.json_ par une _api_.

> I can click a button to show me a new random quote.<br>
> I can press a button to tweet out a quote.


### les contraintes

* une __api__ : htpps://fr.wikiquote.org/w/api
* un fichier _.json_ fourni après une requête
* un traitement JavaScript des données
  * rassembler les données dans un tableau
  * afficher une citation aléatoire après une action
  * proposer l'envoi d'un message _Tweet_
* la forme est libre



### Les étapes à suivre
* le choix d'une source de citations
  * l'__inspiration__


* le choix d'une présentation graphique
  * du __croquis__ à la __maquette__


* la mise en forme (html/css)
  * à l'aide du 'framework' __Bootstrap 4__


* le code (js)
  * des problèmes ...
  * des __SOLUTIONS__


* les tests
  * des __améliorations__



#### 1 - le choix 
## d'une source de citations
https://fr.wikiquote.org/wiki/Carnac


## de la POÉSIE
__beauté__<!-- .element: class="fragment" data-fragment-index="1" --> __sensibilité__<!-- .element: class="fragment" data-fragment-index="2" --><br>
__force__<!-- .element: class="fragment" data-fragment-index="3" --> __évocation__<!-- .element: class="fragment" data-fragment-index="4" --><br>
## *__évasion__*<!-- .element: class="fragment" data-fragment-index="5" -->


### SI FRAGILE


## SI INDISPENSABLE


## un choix ingénu
#### portant bien des
## complications


### le format atypique de la page
les extraits placés entre des balises &lt;span>


### la complexité de l'__api__ Wikimedia
une documentation foisonnante<br>
exhaustive, technique
##### pas beaucoup d'images !


### les écueils
# __CORS__
la bête noire est en gras

<small>(combien d'heures perdues ?)</small>


## __JSONP__
    &callback=?


Oui, c'est bien ça :

=
# __?__


### et quand __tout marche__
# en __local__


## ON FAIT QUOI ?


#### on cherche !


## on trouve !


# WIKIBLURB


#### la bibliothèque de 9bitStudios
#### et Ian C.
la solution<br>
<small>(une des)</small>



#### 2 - le choix
## d'une présentation graphique


# des croquis
### des ébauches
##### des crobards


##### UNE
# idée


##### présenter les extraits en respectant
### les proportions
## d'une page de recueil


### simple
### minimaliste
## efficace


### MAIS
##### de l'idée
##### à la réalisation


### que d'écueils
#### d'embûches<!-- .element: class="fragment" data-fragment-index="1" -->
##### de chausse-trapes<!-- .element: class="fragment" data-fragment-index="2" -->


## Proportion 11x18
### un rapport 1,63


### un peu trop
## radical
pour une page web


#### arrondi à
### 1x1,5


### le placement
conserver les proportions en
'responsive'
### impossible<!-- .element: class="fragment" data-fragment-index="1" -->


### découverte et utilisation
### de la mesure VH
une taille proportionnelle à la hauteur de la page
merci Pierre !<!-- .element: class="fragment" data-fragment-index="1" -->


### les polices de caractères
## Garamond / Baskerville


### Google fonts 
## EB+Garamond
## Libre Baskerville
(titre et 'header')
