# Introducción a CSS

Este es un breve repaso sobre CSS (Cascading Style Sheets), un lenguaje de hojas de estilo utilizado para diseñar la apariencia y el formato de documentos HTML. CSS permite aplicar estilos, como colores, fuentes, márgenes y posicionamiento, a elementos específicos en una página web.

## Tabla de contenidos

1. [¿Qué es CSS?](#qué-es-css)
2. [Sintaxis básica](#sintaxis-básica)
3. [Selectores CSS](#selectores-css)
4. [Propiedades CSS](#propiedades-css)
5. [Modelo de caja](#modelo-de-caja)
6. [Estilos en cascada](#estilos-en-cascada)
7. [Recursos adicionales](#recursos-adicionales)

## ¿Qué es CSS?

CSS (Cascading Style Sheets) es un lenguaje de hojas de estilo utilizado para describir la presentación y el formato de un documento HTML. Con CSS, puedes definir cómo se verán los elementos HTML en una página web, incluyendo el diseño, colores, fuentes, márgenes y más.

CSS se utiliza para separar la estructura y el contenido de un documento HTML de su diseño y apariencia visual. Esto permite una mayor flexibilidad y mantenibilidad al desarrollar y mantener sitios web.

## Sintaxis básica

La sintaxis básica de CSS consiste en un selector y un bloque de declaración. El selector indica qué elemento HTML se va a estilizar, y el bloque de declaración contiene una o más propiedades y sus valores.

Aquí hay un ejemplo básico de reglas CSS:

```css
selector {
  propiedad: valor;
}
```

## Selectores CSS

Los selectores CSS se utilizan para seleccionar elementos HTML a los que se les aplicarán estilos. Hay varios tipos de selectores CSS, incluyendo:

- **Selector de elemento**: selecciona todos los elementos de un tipo específico. Por ejemplo, `p` selecciona todos los elementos de párrafo.
- **Selector de clase**: selecciona elementos que tienen un atributo de clase específico. Por ejemplo, `.mi-clase` selecciona elementos con la clase "mi-clase".
- **Selector de ID**: selecciona un elemento con un atributo de ID específico. Por ejemplo, `#mi-id` selecciona el elemento con el ID "mi-id".

Estos son solo algunos ejemplos de selectores CSS. CSS ofrece una amplia gama de selectores que permiten seleccionar elementos de manera precisa y específica.

## Propiedades CSS

Las propiedades CSS se utilizan para definir cómo se verán los elementos seleccionados. Hay una gran cantidad de propiedades CSS disponibles, que abarcan desde colores y fuentes hasta márgenes y posicionamiento.

Aquí hay algunos ejemplos de propiedades CSS comunes:

- `color`: define el color del texto.
- `font-size`: define el tamaño de la fuente.
- `background-color`: define el color de fondo del elemento.
- `margin`: define los márgenes alrededor del elemento.
- `padding`: define el espacio interno entre el contenido y el borde del elemento.

Estos son solo ejemplos de propiedades CSS. CSS ofrece muchas más propiedades para controlar la apariencia y el diseño de los elementos en una página web.

## Modelo de caja

El modelo de caja es un concepto fundamental en CSS que describe cómo se representa y se coloca un elemento

 en una página web. Cada elemento en CSS se considera una caja rectangular que consta de contenido, relleno, borde y margen.

El modelo de caja se puede controlar utilizando propiedades como `width`, `height`, `padding`, `border` y `margin`. Estas propiedades permiten definir el tamaño, el espaciado y los bordes de un elemento.

## Estilos en cascada

La "C" en CSS significa "cascada", lo que significa que los estilos se aplican en función de un conjunto de reglas y prioridades. Si varios estilos se aplican a un elemento, se utiliza el principio de cascada para determinar cuál prevalecerá.

CSS utiliza la especificidad y la regla "último en ganar" para resolver conflictos entre estilos. La especificidad se basa en la combinación de selectores utilizados y determina qué estilo tiene prioridad. Si hay estilos conflictivos, el estilo definido más recientemente se aplicará.

## Recursos adicionales

- [Documentación oficial de CSS](https://developer.mozilla.org/en-US/docs/Web/CSS): La documentación oficial de CSS proporciona una guía completa sobre las propiedades, selectores y técnicas de CSS.
- [CSS-Tricks](https://css-tricks.com/): Un recurso en línea popular para aprender y explorar diferentes técnicas de CSS.
- [Codecademy CSS Course](https://www.codecademy.com/learn/learn-css): Un curso interactivo en línea que te guía a través de los fundamentos de CSS.
- [CSS Zen Garden](http://www.csszengarden.com/): Un sitio web que demuestra el poder y la flexibilidad de CSS al aplicar diferentes estilos a una misma página HTML.

Este repaso solo cubre los conceptos básicos de CSS. CSS es un lenguaje flexible y potente que te permite diseñar y estilizar páginas web de manera creativa. A medida que te familiarices con los fundamentos, podrás explorar técnicas más avanzadas, como diseño responsivo, animaciones y transformaciones, para llevar tus habilidades de CSS al siguiente nivel.
