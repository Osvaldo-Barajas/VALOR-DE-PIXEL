#OBTENCION DEL VALOR DEL PIXEL DE UNA COORDENADA UTM

Osvaldo Barajas Amezcua, Estefania Guadalupe Hernandez Aldrete

Universidad de Colima, Campus Coquimatlán 28400, obarajas2@ucol.mx, ehernandez21@ucol.mx

RESUMEN

Se pretende hacer un programa con en el apoyo de la librería gdal que pueda 
obtener el valor que hay en el pixel de diferentes coordenadas UTM de una imagen aster.

PALABRAS CLAVE: 

Programa, librería, pixel, coordena-das.

ABSTRACT

It is intended to make a program with the support of the gdal library that 
can obtain the value in the pixel of different UTM coordinates of an aster image.

KEYWORDS: 

Program, librery, pixel, coordenadas.


INTRODUCCION

En este programa principalmente trabajaremos con imágenes aster de tal manera que podamos 
leerla con los colores RGB y obtener las coor-denadas (dimensiones) y el tamaño del pixel de estas.

Coordenadas: El sistema de coordenadas geo-gráficas UTM (Universal Transverse Mercator) se
utiliza para referenciar cualquier punto de la superficie terrestre, utilizando para ello 
un tipo particular de proyección cilíndrica para represen-tar la Tierra sobre el plano.

Colores RGB: Se basa en lo que se conoce como síntesis aditiva de color. Empleando la luminosidad 
del rojo, el verde y el azul en dife-rentes proporciones, se produce el resto de los colores.

Pixel: El píxel es el elemento más pequeño de una imagen gráfica.
Aster: Las imágenes ASTER son una fuente rápida de imágenes satelitales 
georreferencia-das listos para ser utilizado en un software SIG

DESARROLLO

Librerías
GDAL 
Los módulos que tiene gdal nos sirve para abrir la imagen y ver los módulos, además nos ayuda 
a leer los datos de las bandas y después de ello convierte los datos a puntos flotantes, lo 
cual nos ayudará a facilitar el cálculo de Índice de Vegetación 

GDAL significa Geospatial Data Abstraction Library.

Es una biblioteca de software para la lectura y escritura de formatos de datos geoespaciales 
publicada bajo la MIT License por la Fundación OSGeo. Con esta librería se pueden realizar multitud 
de operaciones de transformación y procesamiento sobre gran variedad de datos ráster y vectoriales. 
La librería GDAL es utiliza-da por gran número de paquetes geomáticos como por ejemplo QGIS, gvSIG o 
ESRI Ar-cGIS. Desde los menús de cualquiera de estos clientes SIG podemos acceder a las funciones de 
GDAL utilizando los formularios diseñados para ello.

GDAL tiene como función leer y escribir datos provenientes de ráster geoespaciales además realiza 
otras funciones como exportar imáge-nes, transformar formatos, Re proyectar datos, hacer mosaicos de 
datos entre otras cosas.Una de las funciones que tiene gdal es instalar el controlador de errores que 
captura el error, la clase el mensaje GDAL. 

Metodología
Como primer paso se debe convertir las coor-denadas geográficas a coordenadas UTM con la ayuda de un 
software o una página de inter-net.
 ![PalabrasdelTextoAlternativo](https://github.com/Osvaldo-Barajas/VALOR-DE-PIXEL/blob/master/IMAGENES/UTM.png)
Ilustración 1, Conversión de coordenadas

Después se colocarán las coordenadas donde queremos obtener el valor del pixel dentro del código de Python.
![PalabrasdelTextoAlternativo](https://github.com/Osvaldo-Barajas/VALOR-DE-PIXEL/blob/master/IMAGENES/CODIGO.png)
![PalabrasdelTextoAlternativo](https://github.com/Osvaldo-Barajas/VALOR-DE-PIXEL/blob/master/IMAGENES/CODIGO2.png)
Ilustración 2, codigo de python

MANEJO DE DATOS	

En este programa estamos manejando datos de imágenes aster, para saber valores de diferen-tes coordenadas con 
ayuda de los colores RGB.

Esto lo hemos estado ejecutando en Qgis, Python 2.7 y Python 3.7 con la librería que lleva de nombre 
Gdal, en Windows 10.

RESULTADOS

Como parte de los resultados del valor del píxel de la coordenada geográfica (644554.6542134129, 2138408.476510105) 
se obtuvo el valor de:
20660	6535	85
![PalabrasdelTextoAlternativo](https://github.com/Osvaldo-Barajas/VALOR-DE-PIXEL/blob/master/IMAGENES/RESULTADOS.png)

CONCLUSIONES

Concluyo que fue algo interesante, ya que el manejo de los datos que estuvimos utilizando nos ayudó a 
conocer más librerías, códigos, en más, para nuestra practica sobre los temas.
Además, el resultado del programa es de mucha ayuda en nuestra carrera hablando de las coordenadas UTM.

Hernández Aldrete Estefanía

En conclusión gracias a este proyecto de programación II he comprendido la importancia de la aplica-ción de 
SIG´S y/o librerías o módulos para programar, para eneset e caso obtener los valores del pixel de cualquier 
coordenada UTM

Osvaldo Barajas Amezcua

POSTER

![PalabrasdelTextoAlternativo](https://github.com/Osvaldo-Barajas/VALOR-DE-PIXEL/blob/master/IMAGENES/Obtenci%C3%B3n%20del%20valor%20del%20pixel%20de%20una%20coordenada%20UTM_POSTER1.png)



