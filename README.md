# Cours Processing B1 Ynov Bordeaux
*du 2 mars au 9 mai 2023*

<img src="Structures_Julien_v3ga_Gachadoat_0xc849c3099ad5c9615548b6f31348c5894e23fdacb91687eeeeddd63ae086da8e.jpg" height="400px" /><img src="v3ga_carte_visite_Structures.jpg" height="400px" />

#### Sketches en ligne
✍️ https://editor.p5js.org/v3ga/collections/0chtGIgKA

## Thème
Au croisement du design graphique et de la programmation, ces cours proposeront d’utiliser l'environnement [Processing](https://processingfoundation.org/) dans sa version web [p5.js](https://p5js.org/) pour créer, générer des formes géométriques afin de les imprimer à l’aide d’un [robot traceur](https://www.axidraw.com/) dans la lignée des pionniers de l'art génératif.
Le projet final de ces cours mettra en œuvre ces techniques de programmation et l'utilisation du traceur pour produire des cartes de visites génératives. 

## Objectifs pédagogiques
* découverte de l'histoire de l'art génératif et plus largement du design génératif, évolutions des années 60 à nous jours.
* découverte de la programmation interactive temps réel, productions de visuels animés réagissant à des stimuli : mouvement(s), voix, ... 
* apprendre et maîtriser les concepts fondamentaux de la programmation : variables, boucles, branchements, fonctions. 
* apprendre à développer ses propres outils de création, création d'interface (UI) pour configurer et explorer les potentialités d'algorithmes de créations de formes graphiques.
* insérer ses productions de formes dans un workflow plus général : print, site web, installations interactives.

### Déroulé d'un cours  
Le cours sera consacré au deux tiers à l'étude théorique de concepts de programmation créative avec des références graphiques artistiques et l'autre tiers à la pratique par la réalisation d'un exercice « à chaud » utilisant les notions vues.

### Barême pour les exercices
Pour les exercices que je vous donne, le barême est le suivant (sur 10)
* **rendu en temps et en heure** :point_right: 1 point.
* **respect de la consigne** :point_right: 3 points. 
Le sketch doit être sauvegardé sur votre compte en ligne, l'addresse (URL) doit être insérée dans la colonne correspondante dans le document Google Sheet (à venir). 
* **créativité** :point_right: 6 points. 
J'entends par créativité une recherche graphique personelle et/ou interactive qui peut se faire à partir de sketches vus en classe ou de références que vous trouvez en ligne.

## Cours 01
*Jeudi 2 mars 2023*

### Introduction
* Présentation du travail de Julien Gachadoat.
* Présentation de l'environnement [Processing](http://www.processing.org) et de son « écosystème » (notamment [p5.js](https://p5js.org/))
* Présentation de l'environnement de développement et premières commandes de dessin dans l'éditeur en ligne [editor.p5js.org/](https://editor.p5js.org/) 

### Dessiner avec du code 
* repère de dessin, espace de dessin [p5js / createCanvas](https://p5js.org/reference/#/p5/createCanvas)
* dessin de formes géométriques : [point](https://processing.org/reference/point_.html), [line](https://p5js.org/reference/#/p5/line), [ellipse](https://p5js.org/reference/#/p5/ellipse), [rect](https://p5js.org/reference/#/p5/rect).
* dessin de formes géométriques « composées » : [beginShape](https://p5js.org/reference/#/p5/beginShape) / [vertex](https://p5js.org/reference/#/p5/vertex) / [endShape](https://p5js.org/reference/#/p5/endShape)
* gestion des couleurs ([color](https://p5js.org/reference/#/p5/color)) et des options de dessin([stroke](https://p5js.org/reference/#/p5/stroke), [noStroke](https://p5js.org/reference/#/p5/noStroke), [fill](https://p5js.org/reference/#/p5/fill), [noFill](https://p5js.org/reference/#/p5/noFill), [strokeWeight](https://p5js.org/reference/#/p5/strokeWeight))
* exporter / faire une capture d'écran avec la fonction [p5js / save](https://p5js.org/reference/#/p5/save)

### Références
* [A Modern Prometheus — The history of Processing by C.Reas & B.Fry](https://medium.com/processing-foundation/a-modern-prometheus-59aed94abe85)
* [Welcome to Processing](https://vimeo.com/140600280), vidéo en anglais par [Dan Shiffman](http://shiffman.net/) pour [la fondation Processing](https://processingfoundation.org/).
* [Design by Numbers](https://dbn.media.mit.edu/) de [John Maeda](https://maedastudio.com/)
* [Ben Fry](https://www.benfry.com/) and [Casey Reas](http://reas.com/)
* [Rune Madsen / Computational color](http://printingcode.runemadsen.com/lecture-color/)

#### Exercice
Choisir une des œuvres [« Homages to the square »](https://albersfoundation.org/art/josef-albers/paintings/homages-to-the-square/) de Josef Albers pour le récréer avec du code.
