![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Configuración de Vue.js

## Introducción

En este laboratorio, comenzarás a explorar cómo funciona Vue.js y cómo crear un proyecto utilizando este marco de desarrollo web.

Tus objetivos para este laboratorio serán los siguientes

- Instalar la CLI de Vue.js en tu ordenador
- Crear un nuevo proyecto Vue con un conjunto específico de configuraciones
- Crear un nuevo componente Vue dentro de su proyecto y mostrarlo en la pantalla de inicio
- Mostrar datos de tu JavaScript dentro de tu HTML
- (Bonus) Creación de una función "Hello World" que se dispara al pulsar un botón
- (Bonus) Crear dos rutas diferentes y navegar entre ellas

Seguiremos la guía oficial de Vue.js para la mayor parte de este laboratorio.

## Configuración

- Haz un fork de este repo
- Clona este repositorio
- Abre el LAB y comienza:


  ```bash
  $ cd lab-vue-setup-es
  $ yarn install
  $ yarn dev
  ```

## La presentación

- Al terminar, ejecuta los siguientes comandos:

  ```bash
  git add .
  git commit -m "done "git push origin main # o master si estás trabajando desde un master
  ```

- Crea un Pull Request para que tus TAs puedan comprobar tu trabajo.

## Cómo empezar

<!-- Installing the CLI -->

1. El primer paso antes de crear tu primer proyecto Vue será **instalar la CLI**. Este paso sólo tienes que hacerlo una vez en tu ordenador.

Puedes encontrar las instrucciones [en este enlace](https://cli.vuejs.org/guide/installation.html). Recuerda añadir el comando `-g` para instalar Vue en tu ordenador y no sólo dentro de una carpeta específica.

Si estás trabajando en Mac, recuerda que tendrás que añadir la palabra clave "sudo" antes del comando para que funcione.

<!-- ## Create a new Vue project -->

2. A continuación, procederás a crear un nuevo proyecto. Crear un nuevo proyecto en Vue es tan sencillo como insertar un comando en tu consola una vez que hayas instalado el CLI de forma global. Puedes ver los pasos exactos a seguir [en este enlace](https://cli.vuejs.org/guide/installation.html).

Una vez que estés creando un nuevo proyecto, podrás elegir qué características quieres. En este caso, queremos que elijas manualmente algunas características:

- Babel
- Enrutador
- Linter / Formateador

También queremos que crees un proyecto Vue 2 en lugar de uno Vue 3. Si tienes alguna duda, ¡la documentación es tu mejor amigo!

## Instrucciones

### Iteración 1 | Crea un nuevo componente Vue dentro de tu proyecto y muéstralo en la pantalla de inicio

¿Ya has creado tu primer proyecto? ¡Genial! Ahora empezarás a navegar dentro de la estructura del proyecto.

Para facilitarte la vida, te recomendamos que instales la extensión [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur). Te ayudará a crear nuevos componentes y a añadir funcionalidades de forma más sencilla.

Una vez que hayas creado tu nuevo proyecto y navegado dentro de la carpeta que el CLI ha creado, ¡ya puedes crear tu primer componente Vue!

Aquí tienes una guía útil en caso de que estés atascado: [Cómo crear un](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Vue_first_component) componente Vue.

Consejo profesional: si utilizas la extensión Vetur, sólo tienes que escribir "vue" dentro de tu archivo .vue y elegir la plantilla adecuada para obtener una estructura básica.

Una vez que hayas creado tu nuevo componente, queremos mostrarlo dentro del archivo App.vue. Ya hemos visto en clase cómo hacerlo, pero [aquí tienes una guía paso a paso](https://flaviocopes.com/vue-import-component/) que te ayudará con esta tarea.

### Iteración 2 | Mostrar los datos de tu JavaScript dentro de tu HTML

Ahora que tienes tu nuevo componente, vamos a practicar cómo enlazar los elementos dentro del `<script>` con el `<template>`

Para esto, necesitarás entender la `Interpolación de Texto`. Si necesitas un repaso al respecto, [aquí tienes el enlace a la documentación oficial](https://vuejs.org/guide/essentials/template-syntax.html#text-interpolation).

### Iteración 3 | Bono | Crear una función "Hola Mundo" que se dispare al hacer clic en un botón

Este reto es un poco más avanzado; pero te mostrará lo fácil que es crear y disparar funciones (o métodos, como se llaman en Vue) cuando estás trabajando con un método de JavaScript.

Esto es lo que tienes que hacer:

- Crear un nuevo método llamado `helloWorld()` que muestre la frase "hello world" en la consola.
- Crea un nuevo botón dentro de tu componente y muéstralo en la página de inicio.
- Llame al método `helloWorld()` cuando haga clic en su botón recién creado.

Si necesitas ayuda, [aquí tienes el enlace a la documentación oficial](https://vuejs.org/guide/essentials/event-handling.html#inline-handlers).

### Iteración 4 | Bonus | Crear dos rutas diferentes y navegar entre ellas

Profundizaremos mucho más en el módulo Vue Router en futuras lecciones; pero si quieres un nuevo reto, aquí tienes la última tarea de este laboratorio:

- Si no lo incluiste durante tu configuración inicial, descarga y configura el módulo Router. [Aquí tienes un enlace a la guía oficial](https://github.com/vuejs/router).

Recuerda que sólo tendrás que instalarlo de nuevo si no elegiste incluirlo en tu proyecto cuando lo creaste con la CLI.

- Crea un nuevo componente y regístralo como ruta. De nuevo, [la documentación](https://router.vuejs.org/) es tu mejor amigo aquí.

- Cree una barra de navegación (puede ser tan simple como dos enlaces en la sección superior de la página web) que le permita navegar entre sus componentes.

<br/>

Y ya está.

<br/>

¡Feliz codificación! :heart: