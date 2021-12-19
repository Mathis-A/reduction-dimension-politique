# Titre

### Est-ce que les députés votent comme leur groupe politique ?

Pour répondre à cette question, j'ai utilisé les scrutins de l'assemblée nationale depuis les élections législatives de 2017 jusqu'à décembre 2021 (environ 4000 votes). En réduisant ce nombre important de dimension au plan, on peut reconstituer les groupes politiques, les écarts (et rapprochements) entre les groupes ainsi que les écarts de députés précis par rapport à leur famille politique.
Les résultats sont exposés dans les fichiers html :
- [La représentation 2D classique](https://htmlpreview.github.io/?https://github.com/Mathis-A/reduction-dimension-politique/blob/master/embedding_parti.html)
- [La représentation 2D classique]([embedding_metier.html](https://htmlpreview.github.io/?https://github.com/Mathis-A/reduction-dimension-politique/blob/master/embedding_metier.html))
  - Permet de voir les différents métiers au sein des groupes politiques (la représentation n'est pas forcément bien choisie)
- [La représentation 2D classique]([embedding_3D.html](https://htmlpreview.github.io/?https://github.com/Mathis-A/reduction-dimension-politique/blob/master/embedding_3D.html))
  - Permet de comprendre pourquoi certains points sont positionnés de façon étrange (députés de gauche proche des députés de droite).

Les axes n'importent pas (ils ne sont d'ailleurs pas nommés), seules les distances des points entre eux ont du sens.
L'algorithme essaie de rapprocher les points entre eux : ce n'est qu'un compromis, et certaines distances peuvent se retrouver assez différentes sur les représentations (deux députés différents peuvent se situer proche, par exemple).
