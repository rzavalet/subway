# subway
Encontrar la ruta mas corta en el metro de la CDMX

BFS es un algoritmo de grafos sin pesos que permite encontrar la ruta mas corta entre dos nodos. Su costo es O(V+E).

En este pequeño programa demuestro cómo puede ser utilizado para encontrar cómo llegar de una estación a otra en
el metro de la Ciudad de México. 

Las respuestas encontradas por este programa no considera ni la distancia entre estaciones ni el numero de transbordos.
Ampliando la información del grafo se podría utilizar Dijkstra para encontrar el camino más corto tomando estas otras
consideraciones.

Para ejecutar el programa:

$  python subway.py

--> tlahuac ferreria

Follow this route:

['tlahuac', 'tlaltenco', 'zapotitlan', 'nopalera', 'olivos', 'tezonco', 'periferico_oriente', 'calle_11', 'lomas_estrella', 'san_andres_tomatlan', 'culhuacan', 'atlalilco', 'mexicaltzingo', 'ermita', 'eje_central', 'parque_de_los_venados', 'zapata', 'division_del_norte', 'eugenia', 'etiopia', 'centro_medico', 'chilpancingo', 'patriotismo', 'tacubaya', 'constituyentes', 'auditorio', 'polanco', 'san_joaquin', 'tacuba', 'refineria', 'camarones', 'aquiles_serdan', 'el_rosario', 'tezozomoc', 'azcapotzalco', 'ferreria']

