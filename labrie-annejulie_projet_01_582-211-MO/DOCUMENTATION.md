# Documentation

## Ma démarche
1. J'ai d'abord observé la maquette pour me faire une idée des grandes sections que j'allais avoir de besoin
2. J'ai créé la structure HTML, en y allant une section à la fois
3. J'ai créé mes composants en nommant mes classes
4. Ensuite, j'ai créé mes variables en identifiants toutes les couleurs qui se répétaient, les bordures, les espaces, les tailles de texte, les border-radius, etc.
5. J'ai stylisé la page selon la maquette
6. J'ai fait des révision dans la structure de mon projet

## Choix technique

- Pour mes composantes réutilisables, à certains endroits j'ai préféré ne pas en créé, puisqu'il s'agissait de similarité minimes entre quelques éléments. J'ai plutôt regroupé ces éléments, puisques plusieurs éléments sont similaires, mais tout de même différents. 
(ex: #a-propos, #horaires, #equipe, #contact sont regroupés et #temoignages, #tarifs sont regroupés, car seulement la couleur de fond diffère). Ceux-ci se trouvent en haut de la page CSS pour pouvoir les retrouver facilement. Par contre, cette façon de faire fonctionne seulement parce qu'il y a très peu de sections, mais s'il s'agissait d'un grand site avec des dizaines de scetions, alors utiliser un composant réutilisable serait favorable.s

- J'ai choisi de ne pas nommer les types de texte, pour ne pas se perde avec titre, sous-titre, sous-sous-tritres... J'ai simplement garder les h1, h2, h3, etc. car c'est simple à comprendre à ;a hiérarchie, et cela crée une cohérence dans la taille des différents textes de la page.

- La page est divisée en grandes sections, qui sont elles-même considérées comme des composantes et chaque section contient ses propres informations, ainsi que quelques composants réutilisables qui sont partagés entre les sections, mais il n'y avait pas énormément de composants identitiques entre les sections.

- Les boutons ne sont pas tous exactement pareil, alors ils sont tous stylisés individuellement, avec une classe commune pour les similarités (couleur, radius, etc.)

## Défis rencontrés

- La nomenclature BEM m'a posé quelques problèmes au départ, mais je pense m'être améliorer. Je pense tout de même que ma nomenclature pourrait être encore mieux, je ne suis pas certaine de saisir à 100% le concept BEM.