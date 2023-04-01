# Ejercicio 05 - Flex Panel Gallery

## Sobre el reto

La aplicación es un carrusel de imagenes, que al darle click a un panel este se agranda y muestra más información con animaciones. Si vuelves a hacer click al mismo panel, regresa a su tamaño normal.

## Conocimientos previos

- CSS Transitions
- DOM Manipulation
- HTML Events
- Javascript classList

## Pistas

- Tendrás que añadir evento `click` a los elementos `.panel` para agregar/modificar clases
- Agrega/Quita la clase `open` en los paneles para modificar su tamaño
- Agrega/Quita la clase `open-active` a los paneles para que aparezcan/desaparezcan los textos adicionales. Para esto usa el evento `transitionend`. Este evento tiene una propiedad `e.propertyName` que deberás comparar con `flex-grow` para poder recien modificar la clase `open-active`.
# Demo

<https://jennifertran.github.io/JavaScript30/05%20-%20Flex%20Panel%20Gallery/index.html>
