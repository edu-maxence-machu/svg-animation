# Dessiner en Javascript grâce au format SVG

## SVG c'est quoi ? 

SVG signifie Scalable Vector Graphics.
SVG est l'un des formats vectoriels les plus utilisés. C'est le format préconisé par le W3C.

A la différence de l'image matricielle ("raster graphic" en anglais), l'image vectorielle ("vector graphic" en anglais) est une représentation conceptuelle constituée de primitives géométriques comme les points, les lignes, les courbes et les polygones qui forment des entités décrites par des formules mathématiques. Par exemple, pour représenter un rectangle, on a besoin de savoir l'emplacement de son angle haut et gauche, sa largeur et sa hauteur.
Au lieu de mémoriser une mosaïque de pixels (comme c'est le cas d'une image matricielle), un fichier d'image vectorielle stocke la succession d'opérations conduisant au tracé.
Du fait qu'une image vectorielle est décrite par des entités mathématiques, il est possible d'agrandir ou de réduire sa taille sans aucune perte de qualité, tandis qu'une image matricielle faite d'un nombre fini de pixels ne pourra subir d'agrandissement qu'au prix d'une dégradation sensible appelée crénelage ("aliasing" en anglais).
Il est donc recommandé, dans le cadre du "responsive design" que les logos, schémas d'un site soient des images vectorielles. Par contre pour les photos un format matriciel (png, jpg) est préférable.

Pendant longtemps les images vectorielles au format SVG étaient des fichiers (extension .svg) comprenant surtout du code SVG mais aussi éventuellement du code CSS et JavaScript.
Depuis HTML5 il est possible de dessiner directement dans une page en utilisant SVG ; il suffit que du code SVG soit inclus dans l'élément SVG !
On parle de "SVG interne" (code SVG dans la page web) ou de "SVG externe" (un fichier d'extension .svg).

## La librairie Snap.js

Snap SVG est un framework SVG.
Via un script utilisant les fonctions haut niveau de cette librairie vous créez dans la page un canevas SVG (image vectorielle) et des formes.
Gros avantage par rapport à Inkscape il s'agit d'un générateur de code SVG interne (dans la page) alors qu'Inkscape (ou Boxy SVG) créent des fichiers d'images vectorielles au format SVG.
De plus via Snap SVG, le dessin est non seulement interne mais peut être animé.
Inconvénient : il faut saisir un script, utiliser les méthodes du framework qui correspondent aux balises du langage SVG. Donc il faut connaitre la syntaxe SVG !
Mais pour le moment intéressons nous à la production d'un dessin statique dans la page.

## L'intérêt de savoir manipuler un SVG en code 

On pourraît pense qu'il n'est peut-être pas utile d'apprendre la syntaxe SVG alors que des logiciels de dessin vectoriel tels Inkscape, Illustrator, etc. génèrent du code à ce format.
Cependant ni Inkscape, ni Illustrator ne sont capables de générer du code correspondant à une image vectorielle animée ...

Donc si vous avez de bonnes notions en SVG vous serez capable (avec un éditeur de textes) de compléter le code généré par Illustrator afin d'animer certaines formes OU de vous former rapidement au développement avec le framework Snap SVG.

## Animations

Exemple: https://codepen.io/Jax00/pen/ExaMVPv

## Travail de recherche en groupe 

Voir [recherche.md](recherche.md)