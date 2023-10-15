# UF1-A3-DOCUMENTACION-MP4UF1-Apuntes

Repositorio de Juan Gomez apuntes de GITHUB, MARKDOWN, HTML, CSS, y DISEÑO RESPONSIVE

## Introducción: GITHUB

GitHub es un programa gratuito y online que sirve para hacer repositorio que podamos compartir con los demás dicha información de los repositorios y proyectos pueden ser guardados en la nube.

Para poder inicar, comenzamos descargando el Git la cual es una nueva series de controles para GitHub y la instalamos.

Ahora en la web de GitHub creamos un repositorio, le ponemos un nombre, una descripción de lo que se va hacer en el repositorio, también el acceso lo ponemos público y lo muy importante añadimos el README file para poder dar margen y subir información a nuestro repositorio.

![Alt text](<GitHub part 1.png>)

Ahora copiamos un enlace de nuestro repositorio creado, en nuestra CD local creamos una carpeta para GitHub, abrimos el cmd seleccionamos la carpeta donde guardaremos y ponemos ("git clone https://github.com/JuanjGomez/UF1-A3-DOCUMENTACION-MP4UF1-Apuntes.git"), así duplicaremos nuestro repositorio de la página de GitHub a nuestro sistema. Ahora podemos usar el Visual Studio Code donce podemos poner información en el README.md y lo podemos subir al repositorio con los siguientes comandos del Git.

Después de escribir la información, entramos a la carpeta de nuestro repositorio clonado y abrimos el cmd. El primer comando es (git init), sirve para hacer una configuración inicial al repositorio.

El segundo comando es (git add readme.md), este sirve para subir una información específica y la ubicación a poner o también (git add .), este otro comando en ves de seleccionar una parte de la informcaión, este selecciona todo para poder subir.

El tercer comando es (git commit -m "Título"), este sirve para capturar los cambios y prepararlo para subirlos además, se le puede poner un título entre comillas para dar un nombre al cambio que le haces.

El último comando para subir la información es (git push origin main), este ejecuta los cambios insertandolo los cambios locales y al repositorio en línea.

## Primer Capítulo: MARKDOWN

Ahora pasamos a los comandos y claves que nos sirven en MarkDown, primero para tener este lenguaje de programación en Visual Studio Code debemos insertalo, hacemos clic en Extensiones y buscamos markdownlint, por último lo instalamos.

Con este lenguaje podemos modificar nuestro texto. Para poder poner nuestro texto en cursiva, *Hay dos formas una es con asteriscos* (*texto*), usando dos asteriscos uno al inicio y otro al final del texto, este se pondra en cursiva automaticamente y _la segunda manera es con guiones bajos_ (_texto_), la otra forma es usando guiones bajos como en los asteriscos uno al inicio y otro al final del texto.

Otro formato para dar al texto es ponerlo en negrita. **También haydos formas de poner en negrita**(**texto**), usando dos veces seguidas el asterisco al inicio y final del texto lo pone en negrita y __esta otra forma también puede funcionar__ (__texto__), con doble guiones bajos al inicio y final del texto sirve para poner en negrita.

También se le puede poner el texto en negrita y cursiva al mismo tiempo ***como este ejemplo de negrita y cursiva*** (***texto***), de esta manera el texto saldrá en negrita y cursiva con tres astericos al inicio y final. ___De esta otra manera también se puede hacer las dos___ (___texto___), de esta otra fomra se puede hacer el texto en cursiva y negrita al inicio y final con tres guiones bajos.

1. Primera opción de menú.
2. Segunda opción de menú.
3. Tercera opción de menú.

De esta forma se puede crear una lista ordenada. Poniendo en orden de secuencia cada uno de los temas.

* Primera opción de lista desordenada.
* Segunda opción de lista desordenada.

_ Tercera opción de lista desordenada.
    1. Primer submenú.
    2. Segundo submenú.

_ Cuarta opción de lista desordenada.
    * Tercer submenú.
    * Cuarto submenú.
+ Quinta opción de lista desordenada.
+ Sexta opción de lista desordenada.

Este es un ejemplo de lista desordenada, en ves de usar números para dar un orden a la lista. Para la lista desordenada se usa (*, _, +), estos simbolos se usa una vez al inicio para comenzar la lista desordenada y dentro de las lista tanto ordenada y desordenada se puede poner submenús, dando al tabulador y también se puede usar partes de una lista ordenada o desordenada como (1, 2, 3, etc, o *, +, _), con estas características podemos abrir en submenús.

```
    <html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
<html>
```

Este es un ejemplo de etiqueta para HTML, para ayudar a otros usuarios les haga más facíl su trabajo le añadimos tres comillas a la izquierda (``), al inicio, saltamos espacio y al terminar la etiqueta ponemos otras (```), al final, así se podrá copiar y será más sencillo.

[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

Para añadir un enlace al repositorio se hace de esa manera, ahora al inicio se abre un ([texto]), lo que va dentro de corchete es la forma o texto en la que se ponga el enlace, ahora en el parentesis (enlace "Comentario del enalce"), en esta parte va el enlace y por último se hace un espacio y entre comillas se le añade un comentario que aparecer cuando la se ponga la flecha del mouse sobre esta.

![Esto es una imagen de informática](https://github.com/JuanjGomez/UF1-A3-DOCUMENTACION-MP4UF1-Apuntes/blob/main/Qu%C3%A9-se-hace-en-Inform%C3%A1tica.png "Informática")

Ahora para poner una imagen y que este a la vez sea una enlace para entrar a otra página, primero se debe guardar una imagen en el carpeta de nuestro repositorio, luego subimos con los comandos del git en el cmd. Para entonces ya tendremos la imagen en nuestro repositorio, vamos ahi, copiamos el enlace de la imagen y acontinuación. se pone un signo de exclamación al inicio, ahora se abre corchete ([Aqui va un nombre a la imagen]), después se abre parentesis (Aqui va pegado el enlace "Comentario de la imagen"), dentro de los parentesis se pone el enlace y seguido entre comillas un comentario que salga de esa enlace-imagen.

|Primera Col.|Segunda Col.|3 Col|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|123€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX1|M4|

Ahora la introducción de tablas, en la primera línea como hroizontal van los nombres, en la segunda los guiones representa la cantidad de espacio que de da a cada uno también se puede alinear el texto al centro, izquierda y derecha. por ejemplo (|---------|) es izquierda, (:--------:) es centrada, (--------:) es derecha. Después de eso se pone la información en cada una de las columnas de la manera vertical, siempre dando margen con | para hacer la tabla y se le puede poner un estilo de colores asignando de esta manera (|Estilo cerba|Amarillo|azul|) de esa manera dará colores diferentes.

-[ ] Opción A

-[X] Opción B

-[ ] Opción C

A continuación se hace una lista en la cual es así ("-[X]") Eso dará formato a una lista de tareas y si son cumplidad en el medio va una X.

## Segundo Capítulo: HTML

