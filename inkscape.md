# Imágenes

Las imágenes se guardan digitalmente de dos maneras:

  * Por un lado (Ráster) podemos hacer una matriz de puntos (Mapa de bits) y a cada punto le asignamos un color (Píxel)

Tres colores primarios aditivos : Rojo, Verde y Marrón o mejor conocido como RGB(Red,Green,Brown)

Otra forma de colores primarios es llamada: CMYK(Cyan,Magenta,Yellow,Black)

Propiedaddes de una imagen Ráster:

Resolución. Un mapa de bits tiene un tamaño concreto de A x B

La resoulción se puede expresar de diferentes formas:

-> Nº total de píxeles. Normalmente MP (Megapíxeles), esto es el número que resulta de A x B en millones de píxeles

-> Lineas horizontales. En vídeo se utiliza la cantidad de líneas horizontales, normalmente se asume una proporción concreta entre A y B, por ejemplo 4/3(TV) o 16/9(Cine)

Las líneas horizontales suelen ser :

240p --> (240 píxeles de alto)

480p --> 480 píxeles de alto

720p --> 720 píxeles de alto

1080p --> HD(1080 píxeles de alto)

2k --> 2048 píxeles de alto

4k --> 4096 píxeles de alto

-> Un archivo puede expresar su resolución dicendo A x B

  * Por ejemplo una imagen de 350 x250 píxeles. Se utiliza cuando hablamos de archivos concretos.

NO CONFUNDIR con la resolución de impresión, medida en puntos por pulgad (ppp) o (dpi) dots per inch.

  * Espacios de color

  * Sistemas para detallar los colores :

  * RGB (Red, Green, Blue) para pantallas

  * CMYK (Cyan, Magenta, Yellow, Black) para imprimir

  * Colores indexados -> Toma hasta 256 colores y se usan solo esos --> GIFs

  * Canal (como los 3 canales de RGB) de transparencia. Este canal de llama alfa (α). Los PNG pueden tenerlos, los GIFs o los JPG no.


## FORMATOS COMUNES

 * JPG ( y JPEG) --> Tiene congresión

![](https://sm.ign.com/t/ign_latam/news/c/crunchyrol/crunchyrolls-anime-awards-winners-announced_bnmy.1280.jpg)

 * GIF --> Color indexado. Se puede animar
 
![](https://www.educaciontrespuntocero.com/wp-content/uploads/2019/06/homer.gif) 

 * PNG --> No tiene compresión. Admite alfa

![](https://github.com/miguelamgel1107/1er-trimestre-/blob/main/5853bc61ec0c270fc2f62de5.png)

 * TIFF --> Sin compresión

Otros particulures:

  * PSO

  * RAW (Foto sin comprimir)

Imagen Ráster está hecha de píxeles y tiene formatos los .JPG .GIF .PNG.

# IMÁGENES VECTORIALES

Se define la imagen como un conjunto de formas (Líneas, Puntos,etc) Cada una de estas formas está definida matemáticamente.

Por ejemplo un círculo se define como un relleno.

Forma = Círculo

Radio = 30 píxeles

Borde = 1 ancho, color rosa
## FORMATOS

  * .svg (Scalable vector graphic)

  * .eps

Específicos

  * DWG (Autocad)

  * DXF (AutoCad)

  * 3DM (Rhinoceros)

  * AI (Ilustrator)

Formato mezcla Ráster y vectorial

  * PDF = Portable Document Format

Rasterizamos una imagen, cuando pasamos de una imagen vectorial a una imagen ráster (mapa de bits).

Vectorizar es pasar de un mapa de bits (Imagen Ráster) a formato vectorial.

Las imágenes vectoriales están formadas de formas.

### Ejercicio vectorización
Vamos a tomar la imagen del cuadro del león de Rosa Bonheur.

Esta es la imagen rásterizada original.

![](https://raw.githubusercontent.com/Tabrih/1er-Trimestre/main/El%20Cid.jpg)

[Fuente](https://www.museodelprado.es/coleccion/obra-de-arte/el-cid/19984271-9cb6-476d-8655-f012e1fec1bf)

Abrimos Inkscape

Lo primero es decidir si el programa hará una o más pasadas. Con una única pasada SIEMPRE obtendremos una imagen en blanco y negro(Que podremos colorear después).

Una única pasada tenemos:

  * Corte de luminosidad -> Junta todos los píxeles más oscuras que un umbral.

  * Detección de bordes -> Revisa el contrate entre píxeles

Varias pasadas nos permite hacer una imagen vectorial más compleja, con varios grises o colores. Esto necesita más capacidad de proceso.

Después de importar el león, vamos a ajustr el lienzo, para ello vamos a propiedades de documento --> En tamaño, vamos a ajustar página o contenido selecionamos la imagen y pulsamos el botón Ajustar página a contenido o selección

  * Vectorizamos el león con las siguientes características
      * Múltiples pasadas - Colores - 8 pasadas

  * Borramos el original

  * Guardamos como León 1.svg

  * Subimos al Github

-León 1:

![](https://github.com/miguelamgel1107/1er-trimestre-/blob/main/dibujo1.svg)

-León 2:

Este león lo hice con la opcion de vectorizar mapa de bits, con pasada simple y corte de luminosidad.

Primero hice una con umbral de luminosidad de 0,590 y la hice de color amarillo y la puse de fondo.

luego hice otra pero con un umbral de luminosidad de 0,450 y la hice de color azul marino y la puse de segunda.

Por ultimo hice otra con un umbral de luminosidad de 0,250 y la hice de color rojo un poco claro y la puse encima de todas.

![](https://github.com/miguelamgel1107/1er-trimestre-/blob/main/dibujo2.svg)

-León 3:

![](https://github.com/miguelamgel1107/1er-trimestre-/blob/main/dibujo3.svg)
