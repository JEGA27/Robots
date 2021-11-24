# Robots

En este repositorio se encuentra la solución propuesta a la problemática en la que se encuentran 5 robots en posiciones random en
un almacén también con posiciones random. Además de las cajas en el almacén hay puertas y obstaculos como estantes.
Los robots deben de encontrar los caminos libres para recojer y ordenar todas las cajas apilándolas en grupos de máximo 5 cajas, esto dentro de un tiempo limíte.

Para dar solución a esta problemática en este repositorio se encuentran un archivo pdf y un unitypackage.
El archivo pdf contiene la descripción de la propuesta del programa para la solución, además del diagrama de clases y de protocolos de agentes.
El unitypackage presenta una propuesta gráfica de la solución. Este archivo contiene una escena con un jugador en primera persona dentro de un almacén
con puertas, estantes, cajas, tanques, etc. y robots en posiciones al azar de dos modelos distintos (5 robots pequeños  y dos grandes), de los cuales algunos cargan cajas. 
Estos robots avanzan por los caminos libres de obstaculos siguiendo caminos al azar. Los robots tardan una cantidad de segundos en encontrar un nuevo camino
y tienen una velocidad al azar. Cada robot cuenta con una fuente de luz puntual de diferentes colores e intensidades que se mueve con ellos.

Algunos objetos de la escena estan coloreados por cara con ayuda de pro builder y otros fueron texturizados con mapeo uv también mediante pro builder.
Estos objetos se encuentran en la jerarquía en el siguiente orden y con los siguientes nombres:

Coloreados:
- Colored Barrel
- Colored Barrel 2
- Colored Barrel 2 (1)

Texturizados:
- Box Texture 1: (Robot Box 1 > Box Texture 1 )
- Box Texture 2: (Robot Box 3 > Box Texture 2 )




Recursos utilizados para unity:

Animaciones:
- Mixamo: https://www.mixamo.com

Assets:
- Robot Kyle: https://assetstore.unity.com/packages/3d/characters/robots/space-robot-kyle-4696
- Robot Metallic: https://assetstore.unity.com/packages/3d/characters/robots/robot-metallic-humanoid-171295
- Sci-Fi Warehouse: https://assetstore.unity.com/packages/3d/environments/sci-fi/sci-fi-construction-kit-modular-159280

Códigos: 
- Movimiento random de los robots: https://www.youtube.com/watch?v=RXB7wKSoupI
