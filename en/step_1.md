The Sense HAT LED matrix uses a coordinate system. The numbering begins at **0** (not 1) in the **top left** corner.

![Coordinates](images/coordinates.png)

The blue pixel is at coordinates (0, 2)
The red pixel is at coordinates (7, 4)

You can set pixels (LEDs) individually using the `set_pixel()` method.

To replicate the above diagram you would enter a program like this:

<iframe src="https://trinket.io/embed/python/c57565feac" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
