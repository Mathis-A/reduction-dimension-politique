# Représentations de l'Assemblée Nationale et de la similarité entre nos députés

### Est-ce que les députés votent comme leur groupe politique ?

Pour répondre à cette question, j'ai utilisé les scrutins de l'assemblée nationale depuis les élections législatives de 2017 jusqu'à décembre 2021 (environ 4000 votes). En réduisant ce nombre important de dimensions au plan, on peut reconstituer les groupes politiques, les écarts (et rapprochements) entre les groupes ainsi que les écarts de députés précis par rapport à leur famille politique.

### Résultats

On arrive donc a reconstituer les partis politiques. J'ai essayé de les aligner globalement avec la représentation de l'[échiquier politique](https://fr.wikipedia.org/wiki/%C3%89chiquier_politique), mais leurs positions absolues n'importent que peu. 

On note que LREM, les républicains, et la gauche ont sont peu étalés, mis à part certains députés éloignés. EELV est globalement proche de LREM, malgré certains écarts : notemment Delphine Batho assez proche de la gauche (assez cohérent). UDR et le rassemblement national sont très étalés (attention, le RN n'a que quelques députés à l'AN).

Les résultats sont exposés dans les fichiers html :
- [La représentation 2D classique](https://htmlpreview.github.io/?https://github.com/Mathis-A/reduction-dimension-politique/blob/master/embedding_parti.html)
- [La représentation avec les métiers](https://htmlpreview.github.io/?https://github.com/Mathis-A/reduction-dimension-politique/blob/master/embedding_metier.html)
  - Permet de voir les différents métiers au sein des groupes politiques (la représentation n'est pas forcément bien choisie)
- [La représentation 3D](https://htmlpreview.github.io/?https://github.com/Mathis-A/reduction-dimension-politique/blob/master/embedding_3D.html)
  - Permet de comprendre pourquoi certains points sont positionnés de façon étrange (députés de gauche proche des députés de droite).

### Notes
- Le jeu de donnée semble comporter certaines erreurs mineures.
- Les axes n'importent pas (ils ne sont d'ailleurs pas nommés), seules les distances des points entre eux ont du sens.
- L'algorithme essaie de rapprocher les points entre eux : ce n'est qu'un compromis, et certaines distances peuvent se retrouver assez différentes sur les représentations.
  - Exemple : trois députés de gauche apparaissent proche de LR, cela ne veut pas dire qu'ils votent à droite, cf la représentation 3D.
