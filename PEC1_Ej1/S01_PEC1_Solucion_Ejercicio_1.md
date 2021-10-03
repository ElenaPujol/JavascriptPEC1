![UOC Logo](/images/uoc_masterbrand_2linies_posititiu.jpg)

# Desenv. front-end amb framew. JavaScript - PEC1
###### by Elena Pujol Olmos

<br><br>

## Ejercicio 1 – Preguntas teóricas (2 puntos)

<br>

1. ### La aparición de HTML5/CSS3/JS ha supuesto el nacimiento del desarrollo front-end moderno. (0.75 puntos)

    * #### ¿Cuál es la ventaja del uso de etiquetas semánticas? Nombra y explica al menos 3 de estas ventajas.

        <br>

        La ventaja del uso de etiquetas semánticas és la de definir la naturaleza del contenido que debe incluirse en ella. Tres ventajas serian, por ejemplo:

        1. Posicionamiento en buscadores: los motores de búsqueda se valen de las etiquetas para saber qué tipo de contenido poseen.

        1. Accesibilidad: para usuarios ciegos, los lectores de pantalla organizan la lectura del contenido.

        1. Reusabilidad: La separación del contenido permite que la página sea rediseñada sólo usando CSS.

        <br>

    * #### Cita al menos 3 APIs HTML5 y explica brevemente su funcionalidad.

        <br>

        1. DOM: para manipular, crear, remover y cambiar códigos escritos en HTML y CSS.

        1. Geolocation API: para recoger información geográfica.

        1. Canvas y WebGL: para crear graficos 2D y 3D animados.       

        <br>

    * #### Cita qué opción ofrece CSS3 para conseguir que se apliquen diferentes estilos CSS sobre el mismo elemento en su visualización en diferentes dispositivos (diferentes tamaños de pantalla).

        <br>

        Esta opción permite lo que se llama "webs responsive". Se consigue con la metadata de HTML "viewport" y con la opción "Media Query" de CSS3 (@media). Ejemplo:

        ```css
        @media only screen and (max-width: 600px) {
            body {
                background-color: lightblue;
            }
        }
        ```

        <br>

    * #### Cita al menos 4 de las características principales de TypeScript (importante superset de JavaScript que trataremos en el siguiente capítulo).

        <br>

        1. Fácil de aprender.

        1. Convierte JavaScript en un lenguaje "adulto".

        1. Permite crear código estandarizado.       

        1. funciona bien con librerías y frameworks de Front-End

        <br>

1. ### El lenguaje CSS es muy rígido, poco práctico y ordenado a la hora de programar. Para evitar este problema se han creado los preprocesadores CSS, que ofrecen evidentes ventajas (0.5 puntos)

    * #### Cita al menos 2 de estos preprocesadores.

        <br>

        1. Sass.

        1. Syntax.

        <br>
    
    * #### Cita al menos 4 ventajas que ofrecen estos preprocesadores.

        <br>

        1. Se pueden usar variables que pueden ser utilizadas, por ejemplo, para aplicar el mismo color a varios elementos sin tener que repetir el color RGB en cada uno de ellos, lo que facilita el mantenimiento de las hojas de estilo.

        1. Realizar operaciones y utilizar funciones.

        1. namespaces para agrupar contextos de estilos.       

        1. Anidar estilos relativos a un elemento y selectores.

        <br>
    
    * #### Explica brevemente en qué consisten los sourcemaps.

        <br>

        Un sourcemap es un mapeo que se realiza entre el código original y el código transformado resultado de aplicar una serie de loaders o de otras transformaciones al código original, tanto para archivos JavaScript como archivos CSS, para facilitar el debuggeo de nuestro código.

        <br>
    
    * #### Explica qué es un transpilador.

        <br>

        Un transpilador basicamente es un tipo concreto de compilador que traduce un lenguaje fuente a otro lenguaje fuente de un nivel de abstracción parecido al del lenguaje fuente original.

        <br>

1. ### El flujo de trabajo profesional en front-end hace indispensable el uso de herramientas como controles de versiones y herramientas de gestión de módulos (0.75 puntos).

    * #### Cita al menos dos sistemas de control de versiones y dos herramientas de gestión de módulos.

        <br>

        1. Control de versiones: Git y Subversion.

        1. Herramientas de gestión de módulos: Webpack y Parcel.

        <br>

    * #### Cita y explica al menos 3 comandos de Git.

        <br>

        1. git init: crea un repositorio Git nuevo.

        1. git clone: crea un clon o copia de un repositorio existente.

        1. git commit: registra en el repositorio los cambios realizados en los ficheron.

        <br>

    * #### Cita y explica brevemente las características más definitorias de WebPack.

        <br>

        1. Es un paquete de módulos de JavaScript de código abierto.
        
        1. Aunque está hecho principalmente para JavaScript, también puede transformar HTML, CSS e imágenes.

        1. Toma módulos con dependencias y genera archivos estáticos que representan esos módulos.

        <br>
