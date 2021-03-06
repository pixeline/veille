# Atomic Design

## L'Atomic Design ?! Keksako ??

En résumé, c'est super simple: **Brad Frost et Dave Olsen**, les gars qui ont inventé ce concept, l'appellent **"Construire des éléments, pas des pages".** - Donc ne PLUS concevoir et développer des pages complètes mais concevoir et développer de petits éléments. Des éléments **vraiment petits**, comme un bouton d'une barre de recherche par exemple.

![Barre de recherche](bar.png "atome css")

Le bouton, c'est un *atôme*.  Si vous combinez cet atôme avec d'autres atômes, comme un input de saisie et son label, vous obtenez une barre de recherche. Cette barre de recherche devient donc une molécule. Ensuite, si vous combinez cette molécule à d'autres molécules, comme un menu de navigation et un formulaire de contact :) et vous obtenez un organisme... enfin voilà, je pense que vous avez saisi l'idée. Cet un concept relativement récent pour ceux qui font du Frontend mais les codeurs en backend connaissent déjà bien ce concept, puisqu'on pourrait la comparer une Progarmation Orienté Objet (POO).

![Atome](atome.png "atome css")

### Comment ça se présente ?

On pourrait les regroupper comme ceci :  
![Brad Forst diagrame](http://bradfrost.com/wp-content/uploads/2013/06/atomic-design.png)

    atoms
       _buttons.scss
       _links.scss
       _inputs.scss
    molecules
       _navigation.scss
       _search-form.scss
       _contact-form.scss
    organisms
       _header.scss
       _footer.scss
       _content.scss
    templates
      _sticky-footer.scss
      _grid-2column.scss
      _grid-3column.scss
    pages
      _home.scss
      _about.scss
      _contact.scss


### Ouais mais dans ton exemple les fichiers sont .scss, c'est quoi encore ce machin ? 

#### *(Ou comment j'introduis le SASS dans le cours...)*
#### Citation Wikipédia : 
> Sass est un langage de feuilles de style en cascade (CSS). C'est un langage de description qui est compilé en CSS.
> SassScript est un langage de script pouvant être utilisé à l’intérieur du code Sass. Deux syntaxes existent. 
> La syntaxe originale, nommée « syntaxe indentée », est proche de Haml. La nouvelle syntaxe se nomme « SCSS »  
> et a un formalisme proche de CSS.

#### On a rien compris ...
Ben sachez que moi non plus je n'ai pas compris ! Cela dit je sais que nous allons prochainement voir cela en cours, donc je laisse soin 
aux déformateurs de nous déformer... enfin vous voyez quoi ...

## Pourquoi l'Atomic design ?

En tant que frontend / uix designer , il est essentiel de remettre régulièrement en question notre workflow et nos techniques de co-création, pour être toujours plus efficaces sans perdre de vue la qualité et la cohérence d’un projet.
Avec le nombre croissant de sites web responsives et les nouveaux principes d’applications universelles, la façon dont nous concevons nos interfaces est en train d’évoluer. Nous devons prendre en compte un large panel de tailles d’écrans et de résolutions, et des interfaces qui sortent du cadre habituel des écrans (ex : HoloLens) et l'atomic design permet justement d'être beaucoup modulable...

![Hololens](https://www.sns-it.ca/wp-content/uploads/2015/11/microsoft-hololens-release-price.jpg "Hololens")

### 5 bonnes raisons d'adopter l'Atomic Design 
1. Réutilisabilitable   
2. Mise en page facile à comprendre
3. Processus plus efficace, prototypage plus rapide
4. Structure de fichier plus modulaire
5. Plus facile à mettre à jour et à supprimer des parties du site

## Sources et liens utiles 
* [Brad Frost, le Chuck Norris de l'Atomic Design ]( http://atomicdesign.bradfrost.com/foreword/  "Brad Frost")
* [Sass (Wikipédia)]( https://fr.wikipedia.org/wiki/Sass_(langage) "SASS")
* [Le blog d'Audrey Hacq]( https://medium.com/@audreyhacq/l-atomic-design-une-m%C3%A9thode-de-co-creation-prometteuse-bd9d5fc2b2ad "Blog in french")
