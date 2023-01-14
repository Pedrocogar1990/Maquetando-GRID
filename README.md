# Proyecto de como aprender a maquetar con GRID

## Descripción del proyecto

Este proyecto será una introducción para aprender y adentrarnos en el mundo de la maquetación GRID.

## Contenido de la Publicación

* Index.html contendrá la estructura html del proyecto.
* CSS esta carpeta contendrá el archivo de CSS del proyecto , con el cual daremos estilo a nuestro HTMl
* IMG esta carpeta contendrá las imágenes necesarias del proyecto.

## Desarrollo del Proyecto

Normalmente el primer paso que daremos para maquetar con GRID es definir la estructura que va a
tener nuestra rejilla. Es un paso importante y para evitar problemas después es conveniente realizar
una reflexión sobre ello.
Una vez hemos decidido que estructura queremos usaremos una serie de propiedades para definirla.
Las más importantes para empezar son, bajo mi punto de vista, las siguientes:
* grid-template-columns: Para definir el número y tamaño de las diferentes columnas de mi estructura.
Debo de poner tantos valores de anchura como columnas quiero que tenga el GRID.
* grid-template-rows: Para definir el número y tamaño de las diferentes filas de mi estructura. Debo de
poner tanto valores de altura como filas quiero que tenga el GRID.
* grid-row-gap: Para establecer la separación entre las diferentes columnas.
* grid-column-gap: Para establecer la separación entre las diferentes filas.

## Alineación Horizontal
Por defecto los elementos del GRID ocupan todo el ancho de la celda que le corresponde, pero
podemos optar por otro tipo de alineaciones horizontales dando valores a la propiedad justify-items.
Los diferentes valores que puede tomar son los siguientes:
* start
* end
* center
* stretch que es la opción por defecto.

## Alineación Vertical
Muy similar a lo anterior. Por defecto los elementos del GRID ocupan todo el alto de la celda que le
corresponde, pero podemos optar por otro tipo de alineaciones verticales dando valores a la
propiedad align-items. Los diferentes valores que puede tomar son los siguientes:

* start
* end
* center

## Distribución dentro del contenedor
En determinados casos puede suceder que los elementos del GRID no ocupen todo el ancho o todo
el alto del contenedor GRID. En estas ocasiones puedo distribuir las columnas y las filas usando las
propiedades justify-content (horizontal) y align-content (vertical).

Los Elementos GRID son los hijos directos, dentro del árbol DOM de nuestra página HTML, del
elemento con la propiedad CSS display:grid.
De manera individual podemos modificar las propiedades de estos elementos para conseguir lo
siguiente:
* Definir el área o zona del GRID (rejilla) que va a ocupar.
* Especificar la alineación horizontal del elemento.
* Especificar la alineación vertical del elemento.
Y, además, existen ciertas reglas de colocación implícita que debemos de conocer.
Área del elemento GRID
Para especificar el área que va a ocupar el elemento GRID lo haremos con las siguientes
propiedades:
* grid-column-start
* grid-column-end
* grid-row-start
* grid-row-end
* stretch que es la opción por defecto.

## Alineación horizontal.
La alineación horizontal de un elemento de manera individual se consigue usando la
propiedad justify-self que puede tomar los mismos valores y funciona igual que la propiedad justify-
items que dábamos al contenedor GRID. Estos valores son:
* start
* end
* center
* stretch (por defecto)

## Alineación vertical.
La alineación vertical de un elemento de manera individual se consigue usando la propiedad align-
self que puede tomar los mismos valores y funciona igual que la propiedad align-items que dábamos
al contenedor GRID. Estos valores son:
* start
* end
* center
* stretch (por defecto)
## Colocación Implícita
La colocación implícita de los elementos GRID es lo que sucede cuando colocamos esos
elementos fuera de la estructura del contenedor o cuando no les damos posición.
Cuando colocamos un elemento fuera de la estructura definida para su contenedor GRID podemos
mantener cierto control añadiendo al contenedor (que no al elemento) las siguientes propiedades:
* grid-auto-columns Que dará tamaño a las columnas de separación entre los límites del contenedor y
la posición donde hemos dejado nuestro elemento.
* grid-auto-rows Que dará tamaño a las filas de separación entre los límites del contenedor y la posición
donde hemos dejado nuestro elemento.

En el caso de que no hayamos especificado el área que le corresponde a un elemento de GRID
podemos establecer ciertas reglas del comportamiento mediante la propiedad grid-auto-flow que
añadiremos al contenedor. Esta propiedad puede tomar varios valores:
* row: Rellena primero las filas. Es la opción por defecto.
* column: Rellena primero las columnas. Es la opción por defecto.
* dense: Intenta rellenar primero los huecos por si viene elementos posteriores más pequeño. Hay que
tener cuidado al usar ésta porque puede provocar cambios de orden en los elementos.

## Áreas Grid
Para acabar con el capítulo dedicado a GRID vamos a ver cómo podemos maquetar únicamente
nombrando áreas. Para ello usaremos las siguientes propiedades:
* grid-area en los elementos GRID
* gird-template-area en el contenedor GRID.

** Para profundizar mas en la maquetacion GRID os dejo algunos links **

## Construido con:

* Lenguajes: HTML,CSS.
* Framework: Visual Studio Code.

## Autores

* Pedro Colomina García.
* Con la colaboración de la Docente Isabel Cayuela Pérez.

## Licencia:

* none

## Recursos Adicionales:

[Link](https://www.adictosaltrabajo.com/2018/01/30/maquetacion-con-css-grid/).
[Link](https://www.youtube.com/watch?v=T4t00Hd3qZc).
[Link](https://www.campusmvp.es/recursos/post/como-maquetar-html-con-el-sistema-grid-de-css.aspx).





