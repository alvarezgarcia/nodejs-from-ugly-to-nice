# 01 - Modulos incluídos en el runtime

En este primer capítulo vamos a crear el esqueleto de nuestro servidor web pero con una particularidad: todo el proyecto será
escrito con módulos que son parte del runtime de NodeJS, es decir sin ninguna dependencia externa.
NodeJS cuenta con una batería de módulos incluidos para realizar muchas de las tareas que hoy por hoy son comunes en herramientas
web: publicar un servidor, encriptar archivos,XXXXXXXXXXX
Estos módulos son parte del núcleo de NodeJS y son los que sustentan otros que usaremos posteriormente, pero es indicado para empezar
ver como podemos usarlos a éstos y conseguir los resultados esperados.
Pasemos a la primera parte

## Un servidor mínimo, básico e incompleto

En este apartado vamos a crear nuestro primer servidor y lo vamos a publicar localmente.
Se incluirán las diferentes secciones que lo componen y después será publicado el código completo para asegurarse que esté completo.

Empezamos por un archivo nuevo: `index.js` y empezamos a escribir código:

Para este servidor vamos a necesitar incluir un sólo módulo, éste es: `http`

`var http = require('http');`

Con esta simple línea hemos insertado en nuestro script el módulo del protocolo http.
La función `require` lleva por parámetro un solo módulo a incluir.


