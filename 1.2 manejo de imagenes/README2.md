# Manejo de archivos jpg, png, svg enfocados a optimización web

## Tamaño optimo de una imagen:
El tamaño optimo de una imagen para una pagina web no debería ser mayor a 70kb-100kb y las herramientas que pueden ser utilizadas para lograr esto podrían ser:

### https://tinypng.com/
> reducen tamaño de imagen. muy útiles en JGP.


### https://www.verexif.com/
> Reducen tamaño de imagen mediante de la eliminación de metadatos de la misma.


# Etiquetas multimedia
* ## <.figure>
    > funciona como un <.div> pero para imágenes es decir es semánticamente correcto.
    puede contener una o varias imágenes y ya podemos darle una dimensión y posicionar la etiqueta de figure y la etiqueta img se adaptará a ello.

    * ### <.img src="" alt="">
    > Permite colocar una imagen, tienen atributos como src en el cual se puede agregar una **dirección local** o un **URL** de internet


    * ### <.figcaption>
    > funciona como un atributo **alt=** pero es visualmente apreciable. ademas de que reemplaza a un <.p> ubicado al final de un div lo cual es semánticamente incorrecto.
