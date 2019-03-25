Preguntas te�ricas:

--------------------------------------------------------------------------------

 1- �Qu� es un lenguaje de marcado? �Cu�l es su utilidad? �Qu� es un tag? �Qu� es un atributo?

    Un lenguaje de marcado es una forma de codificar un documento web para que tenga una estructura dada, utilizando etiquetas. La principal utilidad se da en el servicio web, donde las p�ginas web solicitadas son enviadas al navegador cliente, el cual interpreta y decodifica el documento para mostrar debidamente la p�gina web.
    Una etiqueta o tag es una palabra entre los signos < y >, de la forma '<tag>', que da estructura, significado y sem�ntica a lo que viene seguido a esa etiqueta y hasta encontrar la etiqueta de clausura, de la forma '</tag>'.
    Un atributo es una propiedad de una etiqueta y tiene un valor, que puede ser utilizado para darle mejor estructura al elemento (ejemplos: 'height', 'width'), para darle estilo al elemento (ejemplos: 'border', 'background-color'), o bien para manipularlo con otros lenguajes, tales como JavaScript o CSS (ejemplos: 'id', 'class').

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

 2- �Cu�l es la utilidad de HTML? �Qu� conjunto m�nimo de tags debe contener un documento elaborado en este lenguaje? Describa brevemente su utilidad.

    La utilidad de HTML es definir la estructura y el contenido de una p�gina web.
    El conjunto de etiquetas m�nimo que debe tener una p�gina web son:
        <!DOCTYPE html>: Indica que el documento utiliza la versi�n de HTML 5. Siempre va al comienzo del documento.
        <html>: Es la etiqueta ra�z de todo documento HTML.
        <head>: Contiene los metadatos de la p�gina web, el t�tulo, los enlaces a los archivos de estilos, etc.
        <body>: Es el cuerpo del documento. Esta etiqueta contiene todo el contenido de la p�gina web.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

 3- �Cu�l es la utilidad e importancia de los enlaces o links entre p�ginas? �Qu� significa hipertexto? �Un link solo puede apuntar a otra p�gina? �Qu� importancia tiene esto �ltimo?

    Los enlaces o links permiten que con un simple click, los usuarios "salten" de una p�gina web a otra, sin tener que estar escribiendo la URL completa. Le dan agilidad al servicio web.
    Hipertexto o hiperv�nculo es un fragmento de texto que si es clickeado se es redirigido a otra p�gina o a un recurso espec�fico. Suelen aparecer subrayados en color azul para ser distinguidos.
    Los enlaces no necesariamente deben apuntar a otra p�gina web, tambi�n pueden apuntar a un recurso, tales como una im�gen, un video, una ventana para escribir un mail, etc. La importancia de esto es que se pueden crear enlaces con cualquier recurso de Internet.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

 4- �Qu� es el Rendering Engine de un Browser? �Cu�l es el que utiliza cada uno de los 5 browsers m�s conocidos (Chrome, Firefox, Safari, IE-Edge, Opera)? �Cu�l es la importancia de conocer cada uno de ellos en la construcci�n de un sitio?

    El motor de renderizado es el programa que interpreta los documentos de marcado (HTML), recibidos o no desde un servidor, y muestra en la pantalla del usuario la p�gina web con la estructura y el dise�o desarrollados.
    Los motores de renderizado que utilizan los 5 navegadores m�s populares son:
        Chrome: Blink.
        Firefox: Servo.
        Safari: WebKit.
        Internet Explorer: Trident.
        Opera: Blink.
    Es importante conocerlos, ya que al desarrollar una p�gina web, �sta no se ver� exactamente igual en los distintos navegadores, y es com�n probar las p�ginas web en un �nico navegador. Se los debe conocer para asegurar que las p�ginas web que creemos se van a ver lo m�s parecido posible en, al menos, los navegadores m�s populares.