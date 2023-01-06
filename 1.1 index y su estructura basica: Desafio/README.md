# Etiquetas Utilizadas y su explicación


## 1 `<!DOCTYPE html>` :
>Indica al browser en que está interpretando HTML:5.

## 2 `<html lang="es">`:
>Indica al browser que el contenido está en español.

## 3 `<head>`:
>Va todo lo que es importante para el navegador para cargar el proyecto en la forma en la cual fue construido pero no es visual para el usuario final, Dependencias, librerias, CSS.

- ### 3.1 `<meta charset="UTF-8">`
    > Especificación de caracteres especiales como lo son las tildes.

- ### 3.2 `<meta name="description" content="Esta página te mostrará gatos"/>`
    > SEO para mejoras del posicionamiento de las páginas web.

- ### 3.3 `<title>Es mi página</title>`
    > Forma de asinar un título o nombre a la página web.

- ### 3.4 `<meta name="viewport" content="width=device-width, inictial-scale=1.0">`
    > Meta de especificación responsive respecto a los tamaños de letra en distintos dispositivos.

- ### 3.5 `<link rel="stylesheet" href="stile.css">`
    > "rel": el documento que va a cargar es una hoja de estilos y "href": almacena la ruta de esa hoja de estilo.


## 4 `<body>` :
>Va todo el texto, imágenes videos y demás elementos interactivos, en esta sección suelen existir etiquetas de **contenido** y etiquetas **contenedoras** 

- ### 4.1 Etiquetas **contenedoras**
    - #### 4.1.1 `<header>`
        > Presente en una página web siempre y cuando se quiera agregar una barra de navegación, logos, etc.

        * ##### 4.1.1.1 `<nav>`
            > La etiqueta nav brinda un espacio para la Barra de navegación de la pagina web
    - #### 4.1.2 `<main>`
        > Es la main area va fuera del header y después del mismo
        * ##### 4.1.2.1 `<section>`
            > La etiqueta section brinda un espacio en el cual agregar artículos

            * ##### 4.1.2.1.1 `<article>`
                > espacio de texto
        * ##### 4.1.2.2 `<ul>` / `<ol>`
            > unordered lists y ordered lists en donde pueden ir otras etiquetas como `<li>` (list item)

        * ##### 4.1.2.3 `<form action="">`
            >Una zona semánticamente correcta en la cual agregar los **`<inputs>`** anidados cada uno dentro de su respectivo **`<label>`** en un formulario  
            el atributo **`action`** se utiliza para apuntar a URL de bases de datos a la cual se desea enviar los datos captados.

    - #### 4.1.3 `<footer>`
        > Pie de página de la web
    - #### 4.1.4 `<div>`
        > Etiqueta contenedora **comodín** que usualmente implica malas practicas del **HTML semántico**

- ### 4.2 Etiquetas **de contenido**
    - #### 4.2.1 `<li>`
        > Utilizado en las listas ordenadas `<ol>` y listas no ordenadas `<ul>`
    - #### 4.2.2 `<h1>`
        > Etiqueta de título
    - #### 4.2.3 `<h6>`
        > Etiqueta de subtítulo
    - #### 4.2.4 `<p>`
        > Etiqueta de párrafo
    - #### 4.2.5 `<a>`
        > Etiqueta anchor o ancla para agregar links
    - #### 4.2.6 `<label for="label01">`
        >Etiqueta de texto que suele anidar un input
    - #### 4.2.7 `<input id="label01" type="text/date/time/etc">`
        >Entrada con variados tipos de datos  
        **`atributos:`**  
        `id:`Un atributo que debe hacer match con el label para luego con js agregar eventos al label  
        `type:`tipo de input que requiere el cambio, cambia su formato, puede ser ***text***, ***number***, ***date***, ***time***, ***[etc](https://developer.mozilla.org/es/docs/Web/HTML/Element/input "etc")***.  
        `placeholder:`Es un texto opcional que puede ponerse en un `input` para dar ejemplo de qué elementos pueden llenar el lugar.  
        `autocomplete:`es un atributo de la etiqueta `input` que permite al navegador auto completar partes básicas de un formulario siempre y cuando el usuario las haya llenado en otra web y no sé información sensible.  
        `required` es un atributo que hace obligatorio el llenado de input que lo tenga.  
        `list="(id de la <datalist>)`  
        `<option>`
        Es una etiqueta de contenido que encierra un valor al igual que un combobox.  
        puede ir contenida tanto dentro de un `<select>`(no tan bueno) como dentro de un `<datalist>`(perfecto)  

    - #### 4.2.8 `<button>`
        >Etiqueta muy parecida a un input de tipo **submit**, con la diferencia de que es más personalizable, para tener un orden en la forma de programar, debería de usarse los `<input>` dentro de los `<forms>` y los `<button>` en cualquier otro lugar que no sea un form y se necesite un botón de acción.