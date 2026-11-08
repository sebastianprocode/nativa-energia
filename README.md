# Nativa Energía

Sitio web de una tienda educativa de equipos eficientes. Presenta el contexto de la energía, un catálogo interactivo y estimaciones de ahorro en el hogar.

## Páginas

- `index.html`: portada e indicadores del precio de la energía.
- `catalogo.html`: productos, búsqueda, filtros por categoría y carrito.
- `nosotros.html`: integrante y responsabilidades del proyecto.
- `contacto.html`: formulario de demostración, sin envío a un servidor.

## Tecnologías

- HTML, Bootstrap 5 y estilos propios en Sass/CSS.
- JavaScript para generar el catálogo, calcular ahorros y gestionar filtros y carrito.
- Google Fonts para la tipografía Poppins.

## Ejecutar localmente

Abre `index.html` en el navegador. Para recompilar los estilos Sass, instala Node.js y ejecuta desde la carpeta del proyecto:

```bash
npm ci
npm run build:css
```

El comando genera `css/estilos.css` a partir de `scss/estilos.scss` y `scss/_variables.scss`.

## Alcance de las cifras

Las cifras de energía de la portada se presentan como datos de referencia atribuidos a [XM](https://www.xm.com.co/); el precio de bolsa mayorista no necesariamente coincide con la tarifa residencial. La tarifa y los precios de los productos del catálogo son ilustrativos. Los cálculos de ahorro se basan en potencias y horas de uso de ejemplo y no constituyen una cotización.

## Autores

Juan Sebastián Molina — desarrollo, planeación y diseño del proyecto.
