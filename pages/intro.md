# Introducción

#### Astrum es una biblioteca de componentes _front-end_ (_snippets_ y patrones de código) organizados en grupos para su consulta y reutilización en el desarrollo de las aplicaciones de Grupo Preving.

Cada componente está formado dos archivos, *markup.html* y *description.md*, que incluyen el código mínimo necesario para representar un ejemplo del componente junto con una descripción breve del mismo.

Los componentes se agrupan en carpetas, que se representan como apartados. Cada grupo también dispone de un archivo  *description.md* para incluir una descripción explicativa.

DEMO: <http://astrum.nodividestudio.com/pattern-library/>

#### Referencias:

- Componentes basados en **[bootstrap](https://getbootstrap.com/)** 4.1.
- Biblioteca construida con **[astrum](https://github.com/NoDivide/astrum)**.
- Es un paquete de **[node.js](https://nodejs.org/es/)**.
- Se puede ejecutar sirviendo el directorio mediante un servidor web. Para testeo se recomienda **[http-server](http://jasonwatmore.com/post/2016/06/22/nodejs-setup-simple-http-server-local-web-server)** (un ligero servidor local de archivos estáticos que se lanza directamente en la carpeta del proyecto).

#### Instalación en local, extensión y consulta.

Astrum es un paquete de node.js, por lo que para poder ejecutarlo es necesario disponer de este último.

Para poder ampliar la biblioteca es necesario clonar/descargar el repositorio del GitLab de Preving, instalar el paquete en node (<https://github.com/NoDivide/astrum#getting-started>) e inicializarlo en la carpeta en la que esté el repositorio clonado. Esto inicializaría una biblioteca Astrum y permitiría trabajar directamente desde terminal de forma interactiva añadiendo, borrando y editando módulos.

Alternativamente, es mucho más rápido trabajar directamente sobre la estructura de carpetas de la biblioteca añadiendo los componentes directamente y referenciándolos en el archivo *data.json* de configuración.

Se prevé un acceso web para consultarlo más cómodamente sin necesidad de instalarlo en local.
