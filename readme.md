# Semaine 7

Il s'agissait cette semaine de bêtement recopier du code pour utiliser des
fonctionnalités de Bootstrap. **Ne rien comprendre n'apprend rien...** Alors
comme d'autres j'ai cherché.

## [Lorem ipsum]()

Voici donc avec **bootstrap** un groupe de ***jumbotrons*** bien longs, auxquels on peut accéder via un **menu horizontal qui *collapse*** sur petit écran.

    Jumbotron ? élément XXL à la façon des écrans télé géants qui ont pris ce nom - un truc américain probablement. Il est présenté avec un grand titre, un fond gris, il prend toute la largeur de la page sinon les coins sont arrondis.

* Pour mieux comprendre modifié l'aspect du "bouton" menu sur petit écran, ainsi que les couleurs de titres. Pour m'y retrouver aujourd'hui et demain j'ai truffé le code de commentaires.

Des *jumbotrons* donc. Avec *bootstrap.js* (et *jquery* derrière) on y a ajouté un **effet de *scrolling***.

* J'ai ajouté un **second effet, proposé par ManiaxX** sur OpenClassroom, **qui amortit le *scrolling* à la souris** - le premier proposé par l'"exercice" s'appliquait au clic sur menu.

Il s'agissait ensuite de visualiser le paragraphe actif dans le menu. Deux bidules à ajouter sans comprendre dans la balise body... chouette !

* Comme c'est bien beau un menu adapté pour petits appareils, mais qu'on aimerait qu'il se referme quand on a sélectionné notre chapitre (sinon ça empêche de lire !), j'ai cherché pourquoi, et comment changer.

Réponse sur un forum :
  > "Bootstrap's default setting is to keep the menu open when you click on a menu item. You can manually override this behaviour by calling .collapse('hide'); on the jQuery element that you want to collapse."

Suite à quoi j'ai trouvé un bout de code.

    Merci à ceux qui partagent ! Un de ces prochains jours, on saura faire par nous-même....

Enfin, il fallait que chaque chapitre s'affiche seul à l'écran en ajoutant une hauteur aux jumbotrons, les adaptant à la hauteur de l'appareil. Un autre code javascript à recopier sans comprendre. Quoique là le code est nettement plus clair, abordable.
