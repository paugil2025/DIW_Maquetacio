Pràctica 11: Transicions, Animacions i Vídeos -- Pau Gil

Transicions i animacions --css/style.css

* Modificació del menú superior (Sticky): Línies 27 a 33.
  - Es va canviar el menú de dalt posant-lo com a sticky en lloc de static perquè la imatge del hero no tingués aquest gap buit.

* Efecte Hover de la Galeria (Scale, Rotate i Grayscale - Exercici 1): Línies 243 a 248.
  - Vaig haver de modificar el codi perquè funcionés correctament l'overflow: hidden, encapsulant les imatges amb un contenidor div.

* Botó Reservar (Transició lliure de 3 propietats + Animació de pulso): Línies 251 a 267.

* Animació de la Cabecera (@keyframes aparicioText - Exercici 2.1): Línies 269 a 285.

* Segona Animació de 4 frames (@keyframes polsBoto - Exercici 2.2): Línies 298 a 318.

* Contenidor i Capa de Controls del Vídeo: Línies 185 a 217.

* Responsive Media Queries (Tablets i Mòbils): Línies 220 a 240.

---

Estructura i Lògica --index.html

* Estructura del vídeo i capa de controls personalitzats (Exercici 3 i 4): Es troba dins de la secció amb id "video-apartat". S'han amagat els controls natius del navegador per mostrar la capa de controls fosca i transparent amb les icones de Google Fonts.

* Script d'interactivitat del vídeo (Exercici 4): Funcions de JavaScript localitzades a l'etiqueta <script> al final del document per gestionar el play(), pause() i el silenci/volum de la reproducció.

* Lògica d'interactivitat amb Scroll (Exercici 5): Codi JS dins de l'etiqueta <script> que controla el esdeveniment "scroll" de la finestra per aplicar el efecte shrink a la navbar i el autoplay automàtic del vídeo usant getBoundingClientRect() segons si és visible o no a la pantalla.