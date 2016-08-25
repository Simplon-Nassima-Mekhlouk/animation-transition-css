ref : http://letrainde13h37.fr/17/transitions-et-animations-css/

#Les transitions

Une transition CSS est le fait d’animer le changement de valeur d’une propriété (d’une valeur A à une valeur B), comme par exemple le changement de couleur d’un élément de color: red; à color: blue;, ou encore le changement de taille de width: 50px; à width: 100px;. Cette transition intervient lors d’un changement d’état, qui peut être :

L’utilisation de pseudo-classes (:hover, :focus, :active, :checked, etc.) ;
La modification du DOM via JavaScript (ajout de l’attribut class, modification des styles CSS) ;
Le chargement de la page dans certains navigateurs ;
D’autres idées de changement d’état pour lancements de transitions.
Afin de gérer cette transition, cinq propriétés sont définies :

transition-property : la (les) propriété(s) à animer ;
transition-duration : la durée de la transition ;
transition-delay : le délai avant que l’animation ne se lance ;
transition-timing-function : la méthode d’interpolation (départ rapide, lent…) ;
et transition : c’est la propriété raccourcie des quatre précédentes.
