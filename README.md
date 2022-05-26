# Proyecto 4
Alumno: Alberto Espinosa Juárez

Programa Académico: Maestría en Ciencias de la Computación

## ¿Qué contiene el proyecto 4?
El proyecto 4 consiste en utilizar la biblioteca creada en "Proyecto_01" para implementar el algoritmo de Kruska y Prim.

Utilizando la biblioteca de grafos desarrollada en el proyecto 1, implementar los algoritmos de Kruskal (directo e inverso) y Prim de tal forma que calculen el árbol de expansión mínima; es decir, desarrollar los métodos en la clase Grafo:

def KruskalD(self):
def KruskalI(self):
def Prim(self):


Los archivos que contiene la carpeta "Proyecto_04" son: 
+ nodo.py Archivo que contiene la clase que define a un nodo y sus métodos
+ arista.py Archivo que contiene la clase que define a una arista y sus métodos
+ grafo.py y archivos para cada algoritmo. Archivos que contienen la clase que define a un grafo y sus métodos, además, contiene los algortimos descritos para el proyecto 1 y contiene los algoritmos DFS (recursivo e iterativo) y BFS, correspondientes al proyecto 02, así como Dijkstra para el proyecto03 y KruskaID, KruskalI y Prim para el proyecto 4.
+ main.py Archivo que contiene la generación y guardado de cada uno de los grafos, tanto los generados como los calculados.
+ grafo2dot.py Archivo que hace la conversión a lenguaje .dot
+ Carpeta archivos_gv_e_imagenes que contiene por subcarpetas los algortimos con sus correspondientes archivos .gv e imágenes
+ ADA_Proyecto4.ipynb este archivo es un notebook en caso de quererlo replicar en Notebook

## Ejecución en local y en nube (Colab)
Para este proyecto realicé dos versiones
1. Ejecución en nube utilizando Google Colab. Para ejecutar el código se debe ir a la siguiente liga https://colab.research.google.com/drive/1VFn8mDSq4FuwyoU5O2EjgVE7ad49WJab?usp=sharing y ejecutar todas las celdas (iniciando de arriba para abajo). No debería existir problema alguno. Los grafos generados se guardan en la sección de "files" dentro de Google Colab (icono de folder en el menú izquierdo).
2. Ejecución en local. Si se clona el repositorio se puede ejecutar en local. Solo se pide leer antes el archivo grafo2dot pues es importante (solo en local).

## ¿Cómo veo la documentación?
Para revisar la documentación es necesario hacer uso del método *help(método)* que nos brindará información sobre cómo y qué hace un método.

**Ejemplo**

help(guardar_grafo)

**Desplegará información sobre el método guardar_grafo así como también de los parámetros que recibe**

## Resúmen del proyecto 4

### Modelo de malla de pocos nodos

#### Generado
![Grafo en malla de pocos nodos][malla1]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstmalla1] 
![Grafo en malla calculado con pocos nodos KruskalD][malla2]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstmalla2] 
![Grafo en malla calculado con pocos nodos KruskalI][malla3]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstmalla3] 
![Grafo en malla calculado con pocos nodos Prim][malla4]

[mstmalla1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/pocos_nodos/malla30_KruskalD.png
[mstmalla2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/pocos_nodos/malla_30_kruskalI.png
[mstmalla3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/pocos_nodos/malla_30_prims.png
[malla1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/pocos_nodos/grafo_malla_30_nodos.png
[malla2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/pocos_nodos/grafo_malla_30_nodos_KruskalD.png
[malla3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/pocos_nodos/grafo_malla_30_nodos_KruskalI.png
[malla4]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/pocos_nodos/grafo_malla_30_nodos_Prim.png

### Modelo de malla de muchos nodos

#### Generado
![Grafo en malla de muchos nodos][malla11]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstmalla11] 
![Grafo en malla calculado con muchos nodos KruskalD][malla21]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstmalla21] 
![Grafo en malla calculado con muchos nodos KruskalI][malla31]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstmalla31] 
![Grafo en malla calculado con muchos nodos Prim][malla41]

[mstmalla11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/muchos_nodos/malla_500_kruskalD.jpg
[mstmalla21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/muchos_nodos/malla_500_kruskalI.jpg
[mstmalla31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/muchos_nodos/malla_500_prims.jpg
[malla11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/muchos_nodos/grafo_malla_500_nodos.png
[malla21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/muchos_nodos/grafo_malla_500_nodos_KruskalD.png
[malla31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/muchos_nodos/grafo_malla_500_nodos_KruskalI.png
[malla41]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/malla/muchos_nodos/grafo_malla_500_nodos_Prim.png


### Modelo de gilbert de pocos nodos

#### Generado
![Grafo en malla de pocos nodos][gilbert1]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstgilbert1] 
![Grafo calculado con pocos nodos KruskalD][gilbert2]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstgilbert2] 
![Grafo calculado con pocos nodos KruskalI][gilbert3]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstgilbert3] 
![Grafo calculado con pocos nodos Prim][gilbert4]

[mstgilbert1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/pocos_nodos/gilbert_30_kruskalD.jpg
[mstgilbert2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/pocos_nodos/gilbert_30_kruskalI.jpg
[mstgilbert3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/pocos_nodos/gilbert_30_prims.jpg
[gilbert1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/pocos_nodos/grafo_gilbert_30_05.png
[gilbert2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/pocos_nodos/grafo_gilbert_30_05_KruskalD.png
[gilbert3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/pocos_nodos/grafo_gilbert_30_05_KruskalI.png
[gilbert4]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/pocos_nodos/grafo_gilbert_30_05_Prim.png

### Modelo de gilbert de muchos nodos

#### Generado
![Grafo en malla de muchos nodos][gilbert11]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstgilbert11] 
![Grafo calculado con muchos nodos KruskalD][gilbert21]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstgilbert21] 
![Grafo calculado con muchos nodos KruskalI][gilbert31]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstgilbert31] 
![Grafo calculado con muchos nodos Prim][gilbert41]

[mstgilbert11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/muchos_nodos/gilbert_500_kruskalD.jpg
[mstgilbert21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/muchos_nodos/gilbert_500_kruskalI.jpg
[mstgilbert31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/muchos_nodos/gilbert_500_prims.jpg
[gilbert11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/muchos_nodos/grafo_gilbert_500_002.png
[gilbert21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/muchos_nodos/grafo_gilbert_500_002_KruskalD.png
[gilbert31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/muchos_nodos/grafo_gilbert_500_002_KruskalI.png
[gilbert41]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/gilbert/muchos_nodos/grafo_gilbert_500_002_Prim.png


### Modelo de mendes de pocos nodos

#### Generado
![Grafo en mendes de pocos nodos][mendes1]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstmendes1] 
![Grafo calculado con pocos nodos KruskalD][mendes2]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstmendes2] 
![Grafo calculado con pocos nodos KruskalI][mendes3]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstmendes3] 
![Grafo calculado con pocos nodos Prim][mendes4]

[mstmendes1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/pocos_nodos/mendes_30_kruskalD.jpg
[mstmendes2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/pocos_nodos/mendes_30_kruskalI.jpg
[mstmendes3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/pocos_nodos/mendes_30_prims.jpg
[mendes1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/pocos_nodos/grafo_dorogovtsev_mendes_30.png
[mendes2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/pocos_nodos/grafo_dorogovtsev_mendes_30_KruskalD.png
[mendes3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/pocos_nodos/grafo_dorogovtsev_mendes_30_KruskalI.png
[mendes4]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/pocos_nodos/grafo_dorogovtsev_mendes_30_Prim.png

### Modelo de mendes de muchos nodos

#### Generado
![Grafo en mendes de muchos nodos][mendes11]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstmendes11] 
![Grafo calculado con muchos nodos KruskalD][mendes21]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstmendes21] 
![Grafo calculado con muchos nodos KruskalI][mendes31]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstmendes31] 
![Grafo calculado con muchos nodos Prim][mendes41]

[mstmendes11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/muchos_nodos/mendes_500_kruskalD.jpg
[mstmendes21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/muchos_nodos/mendes_500_kruskalI.jpg
[mstmendes31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/muchos_nodos/mendes_500_prims.jpg
[mendes11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/muchos_nodos/grafo_dorogovtsev_mendes_500.png
[mendes21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/muchos_nodos/grafo_dorogovtsev_mendes_500_KruskalD.png
[mendes31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/muchos_nodos/grafo_dorogovtsev_mendes_500_KruskalI.png
[mendes41]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/mendes/muchos_nodos/grafo_dorogovtsev_mendes_500_Prim.png


### Modelo de geografico de pocos nodos

#### Generado
![Grafo en geografico de pocos nodos][geografico1]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstgeografico1] 
![Grafo calculado con pocos nodos KruskalD][geografico2]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstgeografico2] 
![Grafo calculado con pocos nodos KruskalI][geografico3]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstgeografico3] 
![Grafo calculado con pocos nodos Prim][geografico4]

[mstgeografico1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/pocos_nodos/geografico_30_kruskalD.jpg
[mstgeografico2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/pocos_nodos/geografico_30_kruskalI.jpg
[mstgeografico3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/pocos_nodos/geografico_30_prims.jpg
[geografico1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/pocos_nodos/grafo_geografico_30_05.png
[geografico2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/pocos_nodos/grafo_geografico_30_05_KruskalD.png
[geografico3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/pocos_nodos/grafo_geografico_30_05_KruskalI.png
[geografico4]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/pocos_nodos/grafo_geografico_30_05_Prim.png 

### Modelo de geografico de muchos nodos

#### Generado
![Grafo en geografico de muchos nodos][geografico11]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][mstgeografico11] 
![Grafo calculado con muchos nodos KruskalD][geografico21]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][mstgeografico21] 
![Grafo calculado con muchos nodos KruskalI][geografico31]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][mstgeografico31] 
![Grafo calculado con muchos nodos Prim][geografico41]

[mstgeografico11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/muchos_nodos/geografico_500_kruskalD.jpg
[mstgeografico21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/muchos_nodos/geografico_500_kruskalI.jpg
[mstgeografico31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/muchos_nodos/geografico_500_prims.jpg
[geografico11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/muchos_nodos/grafo_geografico_500_01.png
[geografico21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/muchos_nodos/grafo_geografico_500_01_KruskalD.png
[geografico31]: hhttps://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/muchos_nodos/grafo_geografico_500_01_KruskalI.png
[geografico41]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/geografico/muchos_nodos/grafo_geografico_500_01_Prim.png

### Modelo de Erdos y Renyi de pocos nodos

#### Generado
![Grafo en Erdos y Renyi de pocos nodos][erdos1]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][msterdos1] 
![Grafo calculado con pocos nodos KruskalD][erdos2]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][msterdos2] 
![Grafo calculado con pocos nodos KruskalI][erdos3]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][msterdos3] 
![Grafo calculado con pocos nodos Prim][erdos4]

[msterdos1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/pocos_nodos/erdos_30_kruskalD.jpg
[msterdos2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/pocos_nodos/erdos_30_kruskalI.jpg
[msterdos3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/pocos_nodos/erdos_30_prims.jpg
[erdos1]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/pocos_nodos/grafo_erdos_30_200.png
[erdos2]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/pocos_nodos/grafo_erdos_30_200_KruskalD.png
[erdos3]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/pocos_nodos/grafo_erdos_30_200_KruskalI.png
[erdos4]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/pocos_nodos/grafo_erdos_30_200_Prim.png

### Modelo de Erdos y Renyi de muchos nodos

#### Generado
![Grafo en Erdos y Renyi de muchos nodos][erdos11]
#### Calculado con KruskalD
#### Peso MST 
![MST total KruskalD][msterdos11] 
![Grafo calculado con muchos nodos KruskalD][erdos21]
#### Calculado con KruskalI
#### Peso MST 
![MST total KruskalI][msterdos21] 
![Grafo calculado con muchos nodos KruskalI][erdos31]
#### Calculado con Prim
#### Peso MST 
![MST total Prim][msterdos31] 
![Grafo calculado con muchos nodos Prim][erdos41]

[msterdos11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/muchos_nodos/erdos_500_kruskalD.jpg
[msterdos21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/muchos_nodos/erdos_500_kruskalI.jpg
[msterdos31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/muchos_nodos/erdos_500_prims.jpg
[erdos11]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/muchos_nodos/grafo_erdos_500_2500.png
[erdos21]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/muchos_nodos/grafo_erdos_500_2500_KruskalD.png
[erdos31]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/muchos_nodos/grafo_erdos_500_2500_KruskalI.png
[erdos41]: https://github.com/AlbertoEJ/ADA4/blob/main/Proyecto_04/archivos_gv_e_imagenes/erdos_renyi/muchos_nodos/grafo_erdos_500_2500_Prim.png

