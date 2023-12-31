# Tarea-2-Sistemas-Operativos: Escala a grises version secuencial
En la tarea 2 de Sistemas Operativos, se solicita aplicar un filtro a una imagen para transformarla a escala de grises, mediante el metodo de luminosidad( Luminosity Method)

En este README, se explicara que software se necesita en el equipo, que entrega como resultado y como se ejecuta el metodo secuencial, en el cual la matriz de pixeles se va a procesar secuencialmente, es decir, un pixel a la vez.

# Requisitos:
-Ejecutar desde un sistema basado en Debian.

-Tener una imagen a color en el equipo.

-En Debian (y distribuciones basadas en), se debe instalar el paquete libopencv-dev. Para distribuciones basadas en Debian se realiza con el siguiente comando: "sudo apt install phyton3-opencv"

-Se debe instalar g++. En distribuciones basadas en Debian se puede con el siguiente comando: "sudo apt install g++"

# Pasos a seguir para compilar el método:
Paso 1) Entrar a la carpeta en la cual se descargó el proyecto. Esto se puede hacer desde la terminal o de forma gráfica y luego abriendo la terminal desde dicha carpeta.

Paso 2) Ejecutar el siguiente comando: "make -f Makefile_secuencial". De está forma, se comprueba que el programa compilé y esté listo para su uso.

Paso 3) Ejecutar el comando: ./version_secuencial [Nombre imagen] [nombre imagen a escala de grises]

# Ejemplo de la ejecucion
./version_secuencial /home/manu/Escritorio/imagen1.jpg /home/manu/Escritorio/imagen2.jpg.

"/home/manu/Escritorio/imagen1.jpg" es la dirección dentro del computador en que está la imagen que hay que convertir a escala de grises.

"/home/manu/Escritorio/imagen2.jpg." sería la dirección dentro del equipo en la que se guardará la imagen convertida a escala de grises.

Y el resultado es el siguiente:

![imagen (copia)](https://github.com/manu22sg/Tarea-2-Sistemas-Operativos/assets/135477227/680d15d9-df15-4da4-abed-ec6e76d79c9a)
Tiempo de ejecucion: 0.007103000 segundos.

Conversion a escala de grises completada.


# ¿Que entrega como resultado?
Lo que entrega como resultado es la imagen a escala de grises y el tiempo de ejecución que demoro el programa en pintar los pixeles a escala de gris de forma secuencial
# A tener en cuenta
Dependiendo del tamaño de la imagen y del tamaño de la pantalla, es posible que no se muestre como deberia la imagen. Aún así, la imagen que se guarda se ve al mismo tamaño que la imagen original.

