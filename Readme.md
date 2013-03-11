# Bienvenidos a "#DisponibleEnCordoba"

[![Build Status](https://travis-ci.org/colaborativa/DisponibleEnCordoba.png)](https://travis-ci.org/colaborativa/DisponibleEnCordoba)


“#DisponibleEnCordoba” quiere visualizar el patrimonio público sin uso de Córdoba [1]. En Córdoba existen decenas de edificios públicos abandonados en buen estado de conservación. Mientras tanto, numerosas asociaciones, colectivos y organizaciones carecen de espacio [2].

## Descripción

"#DisponibleEnCordoba" es una aplicación Web abierta, disponible en GitHub [18], de geolocalización y visualización de edificios públicos abandonados en Córdoba basada en OpenStreetMaps [6], el servidor de mapas MapBox [7] y GoogleSpreadSheet [8]. Este proyecto de código libre está distribuido bajo licencia MIT [15]. Los textos e imágenes bajo una licencia creative commons CC BY 3.0 [3].

Se basa en datos abiertos en formato JSON y CSV, de manera que cualquier persona pueda acceder a ellos y generar trabajos derivados.

## ¿Cómo contribuir a #DisponibleEnCordoba?

### Añadiendo edificios a la lista
Si queréis contribuir a añadir edificios públicos abandonados al mapa envíanos un email a info@colaborativa.eu incluyendo: 

    - Localización del edificio abandonado
    - Estado actual
    - Fotografías
    - Links a prensa o información oficial.
 
### Desarrollando software

Si queréis contribuir en el desarrollo software del proyecto os recomendamos:

    - Consultar la lista de "issues" o "features" (problemas o mejoras) del proyecto en GitHub, elegir alguno, asignároslo y poneros manos a la obra. ¡Así de fácil!
    - Si has encontrado un problema puedes documentarlo en la lista de "issues" del proyecto en GitHub
    - Si has identificado alguna mejora puedes documentarla en la lista de "features" del proyecto en GitHub 
    - También puedes consultar la lista de "issues" actual y realizar aportaciones a través de comentarios.


Para garantizar una buena coordinación entre todos los contribuidores de "#DisponibleEnCordoba", nos gustaría animaros a seguir una serie de recomendaciones:

    - Consultar la lista de mejoras existentes y solicitar nuevas
    - Documentar "bugs" o comportamientos extraños
    - Listar las tareas pendientes de desarrollo 
    - Utilizar el mismo estilo de código que en el resto del proyecto
    - Antes de enviar un "pull request" de una mejora, asegurarse que funciona correctamente y que ha superado una serie de tests
    - No olvidar referenciar "issues" en Git Commits cuando se resuelvan.

Por nuestro lado nos comprometemos a mantener la lista de "issues" y "features" [16] actualizada en todo momento.

Si no habéis colaborado nunca en un proyecto abierto os recomendamos leer el método de trabajo del equipo de GitHub [4] y en especial la sección de "Contributors".

## Instalación

### Clonar el repositorio para obtener una copia en local

$ git clone git://github.com/colaborativa/DisponibleEnCordoba.git

### Si deseas contribuir al proyecto entonces haz un Fork del repositorio 

Primero hacer click en el botón "Fork" del proyecto #DisponibleEnCordoba en GitHub. [18]

A continuación clonar el "Fork" en tu ordenador:

$ git clone https://github.com/username/DisponibleEnCordoba.git

Para más información sobre qué es un Fork visitar [17].

### Sobre los archivos del proyecto

* /ext/: directorio con librerías javascript de terceros necesarias; jquery, mapbox y underscore
* /img/: directorio con imágenes del proyecto
* /css/: directorio con hojas de estilo CSS
* /js/: directorio con archivos Javascript/jQuery que hemos desarrollado de forma espécifica para "#DisponibleEnCordoba"
    * "dec-google_docs.js v1.0": función que actúa como interfaz con Google spreadsheet
    * "dec-principal.js v1.0": función principal que añade los marcadores en el mapa de acuerdo con la información contenida en Google spreadsheet.
* /docs/: directorio con el código documentado en formato HTML. 
    * "dec-google_docs.html" [20]: documentación del código en "dec-google_docs.js"
    * "dec-principal.html" [19]: documentación del código en "dec-principal.js".

### Dependencias con otras librerías

* Mapbox [9]
* jQuery [10]
* Underscore [11]
* jQuery emailSpamProtection [12]


## Documentación oficial
Más información sobre el proyecto en [1] y [2].
La documentación del código está disponible en [19] y [20].

## Autores y créditos

"#DisponibleEnCordoba" v1.0 es un proyecto impulsado y mantenido por colaborativa.eu [5]. Posteriormente liberado y publicado en GitHub para fomentar su utilización en otras aplicaciones de geolocalización, y su continua evolución y mejora por parte de todo el mundo que desee contribuir al proyecto.

Muchas gracias a todos los contribuidores [16].

"#DisponibleEnCordoba" utiliza el proyecto de código abierto MapBox All rights reserved, Copyright (c), [7]. Consultar los términos de su licencia para más información [13].

"#DisponibleEnCordoba" utiliza el componente de código abierto Underscore, Copyright (c) 2009-2013 Jeremy Ashkenas, DocumentCloud [11]. Consultar los términos de su licencia para más información [14]. 
## Contacto

Puedes escribirnos un email a info@colaborativa.eu.

[1]: http://disponibleencordoba.colaborativa.eu
[2]: http://colaborativa.eu/proyectos/disponible-en-cordoba/
[3]: http://creativecommons.org/licenses/by-sa/3.0/
[4]: http://rdegges.com/successful-github-development
[5]: http://colaborativa.eu
[6]: http://www.openstreetmap.es/
[7]: http://mapbox.com/
[8]: https://drive.google.com/
[9]: http://mapbox.com/mapbox.js/api/v0.6.7/
[10]: http://jquery.org/
[11]: http://underscorejs.org
[12]: http://unckel.de/labs/jquery-plugin-email-spam-protection/
[13]: https://github.com/mapbox/mapbox.js/blob/v1/LICENSE.md
[14]: https://github.com/documentcloud/underscore/blob/master/LICENSE
[15]: http://opensource.org/licenses/MIT
[16]: https://github.com/colaborativa/DisponibleEnCordoba/issues
[17]: https://help.github.com/articles/fork-a-repo
[18]: https://github.com/colaborativa/DisponibleEnCordoba
[19]: http://htmlpreview.github.com/?https://raw.github.com/colaborativa/DisponibleEnCordoba/gh-pages/docs/dec-principal.html
[20]: http://htmlpreview.github.com/?https://raw.github.com/colaborativa/DisponibleEnCordoba/gh-pages/docs/dec-google_docs.html
