# Tarea2 HTML5 + CSS
Tarea 2 LMSGI 2018/2019

La tarea solicita:

> Triau un tema que us interessi i creau-hi un lloc web d'una sola pàgina HTML i un full d'estil extern. Ha d'usar els elements següents.
> 
> # HTML
> 
> - Etiquetes semàntiques d'HTML 5 ( **header**,**footer**, **article**, **section**, **aside**...)
> - Regions desplegables amb **details** i **summary**.
> - Navegació interna amb **nav** i àncores. 
> - Llistes i taules.
> - Material multimèdia (imatge i vídeo)
> 
> # CSS
> 
> - Text: mida de la font, tipus de lletra.
> - Color de fons als títols h1, h2...
> - Model de caixa (padding, border, margin, outline)
> - Vores arrodonides en alguns elements.
> - Pseudo-classes dels enllaços.
> 
> Puntuació
> 
> - 6 punts. Totes les especificacions anteriors.
> - 1 punt. Validació HTML a https://validator.w3.org/
> - 1 punt. Validació CSS a https://jigsaw.w3.org/css-validator/
> - 2 punts. Elements avançats, com ara gràfics SVG, <canvas> o animacions i transicions.
> 
> Pujau els vostres arxius a github i creau-hi un accés amb qualque servei com https://raw.githack.com o  https://pages.github.com/.

Usando estas premisas como referencia, iré dando forma a la web desde la versión 0.1 hasta la final, documentando los pasos más relevantes del proceso. Se conservarán los distintos index en el directorio raiz y se irá comprobando con el validor para asegurarme que estoy construyendo una web sólida y funcional.


### Versión 0.1 HTML básico

- Se crea la estructura básica HTML con las etiquetas semánticas propias de HTML5.
- Se trata de una versión sumamente precaria desde la que se irá construyendo el sitio. La idea es que haya un navegador inicial, un bloque pequeño lateral y un cuerpo principal dividido en 4 secciones principales donde se irán colgando los diferentes artículos.
- Finalmente se decide trabajar con un único index y crear una nueva carpeta con los index antiguos que se irán guardando. La idea es que más adelante se pueda acceder a ellos desde la propia web.
- Con la estructura más o menos definida, se valida y comprueba que está todo correcto.
- https://raw.githack.com/Rocachondo/Tarea2-HTML5-CSS/master/oldindex/index0.1.html


### Versión 0.2 CSS básico

- Con la carpeta css y el archivo theme.css subido, se edita el archivo para dar forma a la página.
- El posicionamiento de los compartimentos está siendo un desastre, al igual que el esquema de colores... Estaba tratando de adaptar unas plantillas del curso pasado pero no está dando buen resultado. Además, la web de raw.githack tarda demasiado en actualizar las modificaciones... Lo mejor será continuar mañana, repasar a fondo las opciones de posición, ancho, largo y empezar desde cero, probablemente tarde mucho menos en acabar esta parte. También probaré a a migrar el repositorio a pages.github que en teoría los cambios son automáticos. 
- Tras muchas horas dedicadas a tratar de ubicar correctamente los elementos, opto por probar el programa Brackets, que al incluir la opción de vista en vivo me da mucha verstalidad a la hora de probar configuraciones. Al estar trabajando de manera local ahora mismo, no quedan registrados los cientes (quizás miles) de commits realizados.
- Se actualiza theme.css, index.html y se crea el index0.2.html
- Por algún motivo que desconozco, githack no está aplicando el CSS como sí hacía ayer, y solo muestra el código html. igualmente, es una versión de la web ciertamente lamentable todavía, pero al menos la estructura principal ya está definida:
https://raw.githack.com/Rocachondo/Tarea2-HTML5-CSS/master/oldindex/index0.2.html

### Versión 0.3 HTML + CSS funcional

- El uso de Brackets acelera considerablemente el proceso de creación y realización de pruebas.
- Se agreaga diverso contenido y se realizan pruebas. Tras mucho tiempo y esfuerzo, no se consigue crear una estructura sólida.


### Versión final HTML + CSS

- Finalmente se opta por volver a hacer el diseño de la web con capas utilizando box-sizing y flexbox. Invertí bastantes horas en documentarmente sobre ésto, pero mereción la pena.
- Se introducen todos los apartados solicitados en la práctica.
- Se validan los archivos locales index.html y theme.css, sin embargo, al tratar de hacerlo por url a través de github da fallo. Se opta por validar el código directamente y se suben 2 screenshot a la carpeta validation.


Espero que sea de su agrado, saludos!
