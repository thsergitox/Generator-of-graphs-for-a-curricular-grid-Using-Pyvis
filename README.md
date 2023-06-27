# Generator-of-graphs-for-a-curricular-grid / Generador-de-grafos-para-una-malla-curricular
With this code all the students of the Universidad Nacional de Ingeniería, will be able to generate the for their curricular mesh with the pdf provided by ORCE of curricular advance. https://www.academico.uni.edu.pe/alumno/avance-curricular After downloading the pdf, the student just needs to place it in the same folder and Voila, your graph will be generated automatically.

To run the code in our computers we will need to download the Ghostscript of the camelot library, this is in charge of the correct reading of the pdf. You can do it in the following link: https://camelot-py.readthedocs.io/en/master/user/install-deps.html

--

Con este código todos los estudiantes de la Universidad Nacional de Ingeniería, podrán generar el para su malla curricular con el pdf proporcionado de ORCE de avance curricular.
https://www.academico.uni.edu.pe/alumno/avance-curricular
Tras descargar el pdf, nomas basta que el estudiante lo coloque en la misma carpeta y Voila!, se generó tu grafo automáticamente.

Para correr el código en nuestros ordenadores necesitaremos descargar el Ghostscript de la libería camelot, este se encarga de la correcta lectura del pdf. Lo pueden hacer en el siguiente link:
https://camelot-py.readthedocs.io/en/master/user/install-deps.html

En la nueva actualización de nuestro proyecto, se usó la biblioteca PyVis, que usa VisJs de javascript, para permitir una visualización más interactivas de nuestros grafos.

Acá un ejemplo con la malla curricular de Computer Sciencie:
![d6267c39-9eea-4cc1-a513-9d1c55c77753](https://github.com/thsergitox/Generator-of-graphs-for-a-curricular-grid/assets/100462105/722f5207-82df-4f72-8d99-efb48fe6fbed)

Además, se implementó el algoritmo de Búsqueda profunda, para encontrar el camino que se debe realizar para llevar cierto, curso.
Acá tenemos un ejemplo para llegar a Análisis de Macrodatos.
![fe4daaa4-ab66-43d4-a7bb-2e18ca5f6923](https://github.com/thsergitox/Generator-of-graphs-for-a-curricular-grid/assets/100462105/5fc3bfb4-6556-4c6a-8273-0e68ffa4c74b)

De igual manera, gracias a la bibliteca de Networkx se implementó el algoritmo de dijkstra:
![d14435c5-e685-4ea4-bf14-f23103518131](https://github.com/thsergitox/Generator-of-graphs-for-a-curricular-grid/assets/100462105/a6afaea4-2383-4efb-9498-42f1afd09f45)
 
Acá otro ejemplo con la malla curricular de Química:
![descarga (1)](https://github.com/thsergitox/Generador-de-grafos-para-una-malla-curricular/assets/100462105/867ad1d0-e7bf-4984-8591-8d7913939ec6)

Acá otro ejemplo con la malla curricular de Ingeniería Física:
![descarga3](https://github.com/thsergitox/Generator-of-graphs-for-a-curricular-grid/assets/100462105/12c6a57b-5a46-4437-8ab3-24bec7702921)

Acá otro ejemplo con la malla curricular de Ingeniera de Sistemas:
![descarga (3)](https://github.com/thsergitox/Generator-of-graphs-for-a-curricular-grid/assets/100462105/f68c3c41-1a17-4f61-812e-a4c8d59fe681)

