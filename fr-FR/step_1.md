La matrice LED du Sense HAT utilise un système de coordonnées avec un axe x et un axe y. La numérotation des deux axes commence à `0` (et non à 1) dans le coin supérieur gauche. Chaque LED peut être utilisée comme un pixel d'une image, et elle peut être adressée à l'aide d'une notation `x, y`.

![Coordonnées](images/coordinates.png)

Le pixel bleu se trouve aux coordonnées `0, 2`. Le pixel rouge se trouve aux coordonnées `7, 4`.

Tu peux régler les pixels (LED) individuellement en utilisant la méthode `set_pixel()`.

Pour reproduire le schéma ci-dessus, tu dois entrer dans un programme comme suit :
<iframe src="https://trinket.io/embed/python/c57565feac" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
