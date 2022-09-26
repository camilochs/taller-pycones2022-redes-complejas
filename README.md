# PyConES 2022 Granada :snake:
## Introducción a las redes complejas en Python [Taller]
**30 septiembre 2022**
Taller a cargo de [Patricio Reyes](https://twitter.com/pareyesv) y [Camilo Chacón Sartori](https://camilochs.github.io/web/)
---

## Motivación

Cuando hablamos de redes complejas nos referimos a conexiones de cualquier tipo: tomarse de la mano con otra persona, los coches que pasan por una calle, los ordenadores conectados a Internet, las personas en una sociedad, etc. todos estos ejemplos contienen conexiones. Mientras más conexiones haya más compleja se vuelve una red. Por tanto, entender el funcionamiento de una red es relevante para entender nuestro mundo.

## Entorno de trabajo

- Binder. Por tanto no es necesario instalar nada, unicamente, se debe acceder al enlace de Binder para cargar el notebook.

## Metodología 

El taller comenzaría con una breve introducción a los grafos, para luego, dar paso a una introducción a las redes complejas (esto podría durar unos 30 minutos). Posteriormente, el plan de trabajo sería el siguiente:

- Primera hora. Presentar un ejemplo sobre redes sociales. Aquí la idea es entender qué es una red social para luego analizarla con código. O sea aprender a crear, manipular y visualizar este tipo de redes usando la biblioteca NetworkX.
- Segunda hora. Presentar un ejemplo sobre redes urbanas (datos espaciales), en particular, usar datos públicos sobre Granada para hacer un análisis sobre las estructuras de sus calles. Para esto se utilizará la biblioteca OSMnx, diseñada para el análisis de redes urbanas.

Las bibliotecas que se utilizaran en el taller son las siguientes:
- NetworkX. Para la creación, manipulación y visualización de grafos.
- OSMnx. Paquete para obtener datos desde OpenStreetMaps y traspasarlos a un grafo espacial. (https://geoffboeing.com/2016/11/osmnx-python-street-networks/).


El trabajo que se presentará en el taller se basa en sus aspectos teóricos y aplicados en dos libros cruciales:
- Network Science, autor: Albert-László Barabási (http://networksciencebook.com/)
- A First Course in Graph Theory, autor: Gary Chartrand.
