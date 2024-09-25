# Índice

1. [Análisis de los Modelos de Ejecución Cliente/Servidor](#análisis-de-los-modelos-de-ejecución-clienteservidor)
2. [Evaluación de los Lenguajes de Programación Web Seleccionados](#evaluación-de-los-lenguajes-de-programación-web-seleccionados)
3. [Estudio sobre la Compatibilidad en Navegadores](#estudio-sobre-la-compatibilidad-en-navegadores)
4. [Mecanismos de Integración entre Lenguajes de Marcas y Programación del Cliente](#mecanismos-de-integración-entre-lenguajes-de-marcas-y-programación-del-cliente)
5. [Evaluación de Herramientas de Programación para Clientes Web](#evaluación-de-herramientas-de-programación-para-clientes-web)
6. [Análisis de Mercado y Diferenciación](#análisis-de-mercado-y-diferenciación)
7. [Biografías](#biografías)
----

# Análisis de los Modelos de Ejecución Cliente/Servidor

Temos varios modelos de ejecución cliente/servidor.

### 1. Modelo Tradicional

El cliente solicita recursos o servicios al servidor y este procesa las solicitudas

- __Cliente ligero :__ 

El cliente realiza pocas tarea siendo el servidor que lleve la mayor parte el proceso.

- __Servidor Pesado :__ 

El servidor es el que maneja toda la lógica de la aplicacion, las consultas a la base de datos y la entrega de datos procesados.


### 2. Modelo Cliente Pesado

En este caso, el cliente es el que lleva la mayor parte del proceso.El servidor solo se limita a enviar los datos en respuesta a lo que solicite el cliente.

- __Cliente pesado :__ 

Gran parte de la logica de la aplicacion, el procesamiento y la interfar ocurre en el cliente.

- __Servidor Ligero:__ 

El servidor se limita principalmente para el intercambios de datos, por ejemplo las APIs REST.

### 3. Modelo de dos capas

Este modelo es habitual de las arquitecturas de cliente servidor, donde el cliente realizan las solicitudes directas al servidor.

### 4. Modelo de tres capas

Este modelo existe, porque existen arquitecturas en niveles adicionales, de hay se denomina modelo de tres capa o arquitectura de tres niveles.En este modelo existe un intermediario entre el cliente y el servidor, que es el que tiene la responsabilidad de aplicar una capa logica. Con esto logramos una ventaja a de mantenibilidad y escalabilidad pero tendremos una mayor complejidad.

# Evaluación de los Lenguajes de Programación Web Seleccionados

### JavaScript

JavaScript es el lenguaje principal que utilizamos en el desarrollo de aplicaciones web de lado del cliente.

- __Ventajas :__ 
    - Amplio soporte en todos los navegadores.
    
    - Numerosas 
    bibliotecas y framework(React,Angular,Vue)que nos facilita el desarrollo.

    - Nos permite crear paginas interactivas.

- __Desventajas :__

    - El DOM de javaScript puede a llegar a ser muy lento al trabajar con HTML.

    - Problemas con la depuracion y localizacion sencilla de errores dn los programas de codigo.

### TypeScript

Es un superconjunto de JavaScript que añade tipado estático opcinal y funciones avanzadas de JavaScript.TypeScript es usado para desarrollar aplicaciones JavaScript que se ejecutara tanto en el lado del cliente como servidor.

- __Ventajas :__
    - Detecta errores en una fase temprana.

    - Amplia la funcionalidad de JavaScript.

    - Proporciona una mejor experiencia de desarrollo para grandes proyectos.

    -Integracion con librerias y frameworks.

- __Desventajas :__

    - Curva de aprendizaje.

    - Tiempo adicional para definir los tipos.



# Estudio sobre la Compatibilidad en Navegadores

La mayoria de navegadores de hoy en dia, son compatibles con HTML,CSS,JavaScript etc.... Pero para que tu aplicacion web tenga una mayor compatiblida, sera mejor validar todo el codigo de tu sitio web.


# Mecanismos de Integración entre Lenguajes de Marcas y Programación del Cliente

Html te proporciona la estructura del contenido web mediante el uso de etiquetas que definen elementos como (botones, formulario, imagenes y texto). Pero por si solo, HTML es estático, por eso tenemos lenguajes de programacion cliente como JavaScript y TypeScript que le agregan interactividad y logica.

Con Javascript podemos manipular los elementos del DOM, que es la representacion interna de una pagina HTML en el navegador.

Tenemos tambien los frameworks y bibliotecas que nos facilitan la integracion de entre los lenguajes de marcas y lenguajes de programacion como son: React, Angular, Vue.js



# Evaluación de Herramientas de Programación para Clientes Web

Las herramientas de programacion para cliente web tenemos React, Vue.js, Bootstrap, Angular, etc...

- __React :__ Es una bibliteca de JavaScript flexible y tiene una cierta popularidad para crear interfaces de usuario. React te permite el manejo del estado de forma eficiente y el uso de componentes reutilizables. Se usa mucho para las aplicaciones web dinamicas y la utilizan grandes compañias como por ejemplo Facebook.

- __Vue.js :__ Es muy similar a React, tiene mas facilidad de aprender para nuevos desarrolladores nuevos. Vue nos permite construir componentes reutilizables con una estructura clara que integra HTML,CSS y JavaScript.

- __Bootstrap :__ Esta herramienta te permite trabajar rapidamente con el front-end y nos asegura que nuestra aplicacion web sea responsiva y visualmente atractiva. Es uno de los frameworks mas populares de CSS.

- __Angular :__ Es un Frameworks de JavaScript desarrollado por Google. Angular nos permite construir aplicaciones webs mas robustas y escalables. A diferencias de bibliotecas como React y Vue, Angula nos ofrece una solucion mas completa porque nos proporciona herramientas para todos los apectos para el desarrollo de las aplicaciones web.


# Análisis de Mercado y Diferenciación

Analizando el mercado, no he encontrado ningun tipo de aplicacion similar a la mia, lo que he encontrado a sido aplicaciones web por seraparado, mi aplicacion web seria todo en uno la gestion de bandas con sus calendarios, gestion de ensayo, gesAnálisis de Mercado y Diferenciacióntion de la economia etc....


# Biografías

### Analisis modo ejecucion cliente/servidor
https://www.daemon4.com/empresa/noticias/arquitectura-cliente-servidor/

https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor


### Evaluación Lenguajes de programacion

https://keepcoding.io/blog/porque-usar-javascript/

https://blog.hubspot.es/website/ventajas-y-desventajas-de-javascript

https://medium.com/@alejodev95/introducci%C3%B3n-a-typescript-9740a71aaaee

### Estudio sobre la Compatibilidad en Navegadores

https://www.mouser.es/browsersupport/?srsltid=AfmBOoo1WzCsZSj24-U94aX5laWZv3tIZfYqkJTejDAqQ-NdsIQ3QaCz

https://www.lawebera.es/xhtml-css/compatibilidad-web-navegadores.php


### Mecanismos de Integración entre Lenguajes de Marcas y Programación del Cliente

https://keepcoding.io/blog/lenguajes-desarrollo-web/

https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-client-side-web-technologies

https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards


### Evaluación de Herramientas de Programación para Clientes Web

https://www.monocubed.com/blog/web-development-tools/

https://www.codecademy.com/resources/blog/best-web-development-tools-codecademy-developers-weigh-in/