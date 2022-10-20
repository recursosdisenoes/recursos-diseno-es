# HTML
Etiquetas: #desarrollo #HTML

## Qué es
HyperText Markup Lenguage (...)

Es un [[Lenguaje de marcado]].

## Etiquetas HTML

^f96a7a

#### Etiquetas de tipo caja (block)
Son aquellas que actúan como bloque, esto es, por defecto ocupan todo el ancho disponible en la página. Todas ellas se deben abrir y cerrar adecuadamente.  
  
-   Las etiquetas **h1, h2, h3, h4, h5 y h6** nos permiten crear títulos de manera jerárquica, siendo **h1** el más grande y **h6** el más pequeño, y se pueden añadir en cualquier parte del **body**, si bien es importante seguir el orden jerárquico de importancia del titular.
-   La etiqueta **div** hace referencia a un bloque que puede incluir texto, imágenes, otras etiquetas, etc. Las etiquetas ya vistas **body**, **header**, **nav**, **section**, **article** y **footer** se comportan como **div**.
-   La etiqueta **p** permite definir un párrafo de texto.
  

#### Etiquetas de tipo texto (inline)
Son aquellas que actúan en un trozo de texto, esto es, por defecto solo ocupan el ancho necesario del texto al que encierran. Todas ellas se deben abrir y cerrar adecuadamente.  

-   La etiqueta **span** hace referencia a un trozo de texto en línea que se agrupa con la idea de luego aplicarle ciertos estilos, como veremos más adelante
-   La etiqueta **mark** fue agregada para resaltar parte de un texto que originalmente no era considerado importante pero ahora es relevante acorde con las acciones del usuario. El ejemplo que más se ajusta a este caso es un resultado de búsqueda.
-   La etiqueta **em** es para indicar énfasis, reemplazando la etiqueta **i** que se utilizaba antes.
-   La etiqueta **strong** es para indicar importancia, marcando en negrita el texto dentro de ella, y sustituye a la etiqueta **b** que se utilizaba antes.
-   La etiqueta **u** permite subrayar el texto al que encierra.
-   La etiqueta **small** tiene el propósito de presentar la llamada letra pequeña, y se utiliza en pies de foto, figuras, footers, etc.
-   La etiqueta **cite** se utiliza para presentar títulos de libros, películas, frases célebres, etc.
-   La etiqueta **time** nos permite declarar un texto comprensible para humanos y navegadores que representa fecha y hora.

#### Etiqueta para enlaces
La etiqueta **a** permite crear un enlace a otra página o a otro lugar de la página.  
  
También actúa en un trozo de texto, esto es, por defecto solo ocupa el ancho necesario del texto al que encierran, que también podría ser una imagen o una etiqueta de bloque. Se debe abrir y cerrar adecuadamente, así como rellenar sus atributos para que funcione correctamente:  

-   **target** para indicar si el enlace se abre en una pestaña nueva (__blank_) o en la mima ventana (por defecto o __self_
-   **href** para indicar a donde deben apuntar
-   Si al inicio de **href** se incluye el texto _mailto:_ seguido de una dirección de email, se abrirá la aplicación de correo electrónico por defecto del ordenador.
-   Si al inicio de **href** se incluye el texto _tel:_ seguido de un teléfono que incluya el prefijo de país, se abrirá la aplicación de telefonía por defecto del ordenador.
-   Si al inicio de **href** se incluye el texto _whatsapp://send?text=_ seguido de un texto, se abrirá WhatsApp para enviar ese texto a un contacto.
-   Si al inicio de **href** se incluye el símbolo _#_ seguido de un identificador del que hablaremos más adelante, se enlazará a un elemento concreto de la misma página.

#### Etiqueta para imágenes
La etiqueta **img** permite insertar una imagen en la página mediante una referencia al archivo de la misma. Es la única etiqueta, junto con el retorno de carro (**br**) y la línea horizontal (**hr**) que no tienen que ser cerradas.  
  
Los dos atributos que debe incluir son:  
-   **src** para indicar la ruta (relativa o absoluta) del archivo que contiene la imagen
-   **alt** para indicar un texto descriptivo (título) de dicha imagen.
-   Los atributos **width** y **height** se consideran obsoletos y no se deben utilizar. Cuando veamos los estilos CSS veremos como aplicarlos adecuadamente.

Adicionalmente, en HTML5 recomienda encerrar la etiqueta **img** dentro de una etiqueta superior de bloque llamada **figure**, que a su vez puede incluir una de **figcaption** para el pie de foto.  
  

#### Etiquetas para listas
-   La etiqueta **ul** permite encerrar un conjunto de ítems de lista **li** de forma no numerada (por defecto utiliza _bullets_)
-   La etiqueta **ol** permite encerrar un conjunto de ítems de lista **li** de forma numerada (por defecto utiliza números normales)

#### Etiquetas para tablas
La creación de una tabla comprende la utilización de varias etiquetas de forma jerárquica, a saber:  

-   **table** para iniciar y cerrar una estructura de tabla.
-   **tr** para iniciar y cerrar cada fila de la tabla.
-   **td** para iniciar y cerrar cada columna de la tabla.

Existen varias etiquetas y atributos más relacionados con las tablas, pero dado que no las vamos a utilizar mucho, no se adjuntan aquí, Puedes consultarlos en [HTML Tables](https://www.w3schools.com/html/html_tables.asp).  
  
#### Etiquetas para comentarios
Como ya habrás podido apreciar, los comentarios en html empiezan con el símbolo **<!--** y terminan con el símbolo **-->**.  

Pueden ser de una sola línea o multilínea.

---

[[HTML Boilerplate]]

[[head]]

[[Introducción a maquetación web (HTML y CSS)]]
[[Markdown]]
[[CSS]]