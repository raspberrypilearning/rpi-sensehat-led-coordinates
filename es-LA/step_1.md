La matriz LED de Sense HAT utiliza un sistema de coordenadas con un eje x- y un eje y-. La numeración de ambos ejes comienza en `0` (no 1) en la esquina superior izquierda. Cada LED puede usarse como un píxel de una imagen, y se puede abordar usando una notación `x, y`.

![Coordenadas](images/coordinates.png)

El píxel azul está en las coordenadas `0, 2`. El píxel rojo está en las coordenadas `7, 4`.

Puedes configurar píxeles (LEDs) individualmente utilizando el método `set_pixel()`.

Para replicar el diagrama de arriba, debes introducir un programa como este: <iframe src="https://trinket.io/embed/python/c57565feac" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
