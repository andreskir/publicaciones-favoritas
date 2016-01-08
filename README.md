Ejercicio PublicacionesFavoritas
=======

### Introducción
Esta es una aplicación que permite buscar publicaciones de MercadoLibre dentro de la categoría Computación.
Cada publicación tiene a la izquierda un corazón que al hacer click debería guardarse como favorito. Y al hacer click en una publicación marcada como favorita, debería dejar de ser favorita.
El problema es que cada vez que se refresca la página, los favoritos se pierden.
El objetivo del ejercicio es conseguir que la aplicación recuerde las publicaciones favoritas por más que se recargue la página, utilizando [LocalStorage](https://github.com/grevory/angular-local-storage).
Desarrollar los tests unitarios que crea necesarios.

### Tecnologías

- [AngularJs](https://angularjs.org/): MVW (Model-View-Whatever), resuelve concerns de vista, DI, comunicación con servidor, etc
- [Grunt](http://gruntjs.com/): task runner para automatizar la tarea de levantar el servidor y refrescar ante un cambio en el código

### Cómo correr la aplicación y los tests?

- [Instalar Node.js](https://nodejs.org/en/download/)
- Instalar Grunt `npm install -g grunt-cli`
- Instalar Bower `npm install -g bower`
- [Instalar Ruby](http://rubyinstaller.org/)
- Instalar Compass `gem install compass`
- Instalación de dependencias / setup inicial: `npm install && bower install`
- Servidor: `grunt serve`
- Tests: `grunt test`
