# Implementación de archivos de video en una página web.

# Etiquetas de video
* ## `<section>`
    > Espacio predilecto para la implementación de un video

    * ### `<video>`
        > Permite colocar un video, tienen atributos como:  
    **controls**: el cual agrega controles para reproducir, pausar y volumen.  
    **preload="auto"**: hace que el video se empiece a renderizar al momento de entrar en la página web  
	
        * #### `<source>`
            >Permite agregar varios directorios para que el navegador pueda reproducir un video en caso de que no tenga el tipo de archivo correcto y se utiliza de la siguiente manera:  
            `<source src="./mouseDelivery.mp4#t=10,50">`  
            **src="./mouseDelivery.mp4#t=10,50"**: el atributo src indica el directorio del video y el "#t=10,50" está indicando un umbral desde donde el cual se empezará y terminará de reproducir.



    * ### `<figcaption>`
        > funciona como un atributo **alt=** pero es visualmente apreciable. ademas de que reemplaza a un <.p> ubicado al final de un div lo cual es semánticamente incorrecto.
