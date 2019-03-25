Preguntas teóricas:

--------------------------------------------------------------------------------

 1- ¿Qué es un lenguaje de marcado? ¿Cuál es su utilidad? ¿Qué es un tag? ¿Qué es un atributo?

    Un lenguaje de marcado es una forma de codificar un documento web para que tenga una estructura dada, utilizando etiquetas. La principal utilidad se da en el servicio web, donde las páginas web solicitadas son enviadas al navegador cliente, el cual interpreta y decodifica el documento para mostrar debidamente la página web.
    Una etiqueta o tag es una palabra entre los signos < y >, de la forma '<tag>', que da estructura, significado y semántica a lo que viene seguido a esa etiqueta y hasta encontrar la etiqueta de clausura, de la forma '</tag>'.
    Un atributo es una propiedad de una etiqueta y tiene un valor, que puede ser utilizado para darle mejor estructura al elemento (ejemplos: 'height', 'width'), para darle estilo al elemento (ejemplos: 'border', 'background-color'), o bien para manipularlo con otros lenguajes, tales como JavaScript o CSS (ejemplos: 'id', 'class').

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

 2- ¿Cuál es la utilidad de HTML? ¿Qué conjunto mínimo de tags debe contener un documento elaborado en este lenguaje? Describa brevemente su utilidad.

    La utilidad de HTML es definir la estructura y el contenido de una página web.
    El conjunto de etiquetas mínimo que debe tener una página web son:
        <!DOCTYPE html>: Indica que el documento utiliza la versión de HTML 5. Siempre va al comienzo del documento.
        <html>: Es la etiqueta raíz de todo documento HTML.
        <head>: Contiene los metadatos de la página web, el título, los enlaces a los archivos de estilos, etc.
        <body>: Es el cuerpo del documento. Esta etiqueta contiene todo el contenido de la página web.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

 3- ¿Cuál es la utilidad e importancia de los enlaces o links entre páginas? ¿Qué significa hipertexto? ¿Un link solo puede apuntar a otra página? ¿Qué importancia tiene esto último?

    Los enlaces o links permiten que con un simple click, los usuarios "salten" de una página web a otra, sin tener que estar escribiendo la URL completa. Le dan agilidad al servicio web.
    Hipertexto o hipervínculo es un fragmento de texto que si es clickeado se es redirigido a otra página o a un recurso específico. Suelen aparecer subrayados en color azul para ser distinguidos.
    Los enlaces no necesariamente deben apuntar a otra página web, también pueden apuntar a un recurso, tales como una imágen, un video, una ventana para escribir un mail, etc. La importancia de esto es que se pueden crear enlaces con cualquier recurso de Internet.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

 4- ¿Qué es el Rendering Engine de un Browser? ¿Cuál es el que utiliza cada uno de los 5 browsers más conocidos (Chrome, Firefox, Safari, IE-Edge, Opera)? ¿Cuál es la importancia de conocer cada uno de ellos en la construcción de un sitio?

    El motor de renderizado es el programa que interpreta los documentos de marcado (HTML), recibidos o no desde un servidor, y muestra en la pantalla del usuario la página web con la estructura y el diseño desarrollados.
    Los motores de renderizado que utilizan los 5 navegadores más populares son:
        Chrome: Blink.
        Firefox: Servo.
        Safari: WebKit.
        Internet Explorer: Trident.
        Opera: Blink.
    Es importante conocerlos, ya que al desarrollar una página web, ésta no se verá exactamente igual en los distintos navegadores, y es común probar las páginas web en un único navegador. Se los debe conocer para asegurar que las páginas web que creemos se van a ver lo más parecido posible en, al menos, los navegadores más populares.