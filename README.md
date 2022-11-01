# EIT__59965__Maquetado--HTML5.CSS3
Comision #59965 - Maquetado HTML5 &amp; CSS3

---
## Cursada : Lunes y Miercoles de 20 a 22 hs.

---
## Clase del 26 de Octubre de 2022

En la clase de hoy vimos :

 - Imagenes
 - Background
    - Compatibilidad de navegadores : Etiquetas `-moz` (Firefox), `webkit` (Safary - MacOs & iOS) y `*.Microsoft.*` (Internet Explorer).
    - Propiedades :
        1. Direccion o origen : `background : url(...) ;`
            Acepta URL's tipo http y rutas locales ./
        2. Color : `background-color : ...`.
            Colores HEX , HSL, RGB, etc.
                2.A. Gradientes
                2.B. Colores plenos.
        3. Imagenes : `background-image : url(...)`
            Fondos con archivos .png .jpg .aviff .webp
        4. Repeticion : `background-repeat`.
            4.A. `no-repeat` --> No se repite.
            4.B  `repeat` --> Se repite
        5. Posicionamiento : `background-position`
            Ubicacion en los ejes X e Y.

        background : URL + posicion + Repeticion + color = `background : .
 
 - Bordes :
    - Propiedad : border-style + border-color + border-width
    - Parametros :
        1. Grosor de la linea (px, rem, em, % ).
        2. Color (RGB, HSL , HEX).
        3. Estilo de la linea (solida, doted, double, etc.)
        4. Variables del root.
        Ejemplos = `border : 1rem var( --c_red100 ) var( --b_solid ) `
 - Border Radius :
    - Propiedad : medida (relativas y absolutas).
    - Border-radius-left / Border-radius-right
 
 - Sombras
    - Propiedad : valores absolutas (px).
    - Parametros :
        1. Ubicacion eje x
        2. Ubicacion eje y
        3. Color (acepta variables)

    1. Sombras de elementos o cajas `box-shadow`
    2. Sombras de textos : `text-shadow`

 - Uso del reset y normalizador
    reset.CSS
        https://raw.githubusercontent.com/lodela/reset-CSS/main/reset.css
    normalizer.CSS3
        https://raw.githubusercontent.com/necolas/normalize.css/master/normalize.css

---
## Clase del 31 de Octubre de 2022

Temas a tratar :

    - Repaso de HTML5
    - Repaso de propiedades de accesibilidad.
    - Animaciones.
    - Etiquetas :hover :before :after
