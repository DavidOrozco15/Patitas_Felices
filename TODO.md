# Plan para Agregar Nueva Sección "Misión-Visión" en Patitas Felices

## Información Gathered
- **Estructura Actual**: La sección "seccion-mision-vision" estaba vacía en index.html. Las secciones anteriores usan contenedores centrados (max-width 1200px), fondos beige o blanco, y elementos como tarjetas grises con sombra.
- **Estilos Existentes**: En styles.css, hay clases como .seccion-dias-container para layout grid, .dias-texto para tarjetas (fondo gris #F8F8F8, sombra, texto centrado). Responsividad en tablet.css (max-width 1024px) y celular.css (max-width 767px) ajusta tamaños y layouts a 1 columna.
- **Imágenes**: Usuario especificó "gato-azul.png" como fondo; usada correctamente.
- **Contenido**: Nueva sección con imagen de fondo, y una tarjeta interna similar a la de "Días" (cuadro gris con sombra, texto centrado). Texto: "Nuestra Misión: Rescatar y proteger a los animales abandonados. Nuestra Visión: Un mundo donde cada animal tenga un hogar amoroso."
- **Tamaño**: Igual a secciones anteriores (ancho completo, padding 20-60px, centrado).

## Plan
- [x] Editar index.html: Agregar contenido HTML dentro de .seccion-mision-vision (div con tarjeta de texto).
- [x] Editar css/styles.css: Agregar estilos para .seccion-mision-vision (background-image con gato-azul.png, layout grid, y .mision-texto similar a .dias-texto con rgba para semi-transparencia).
- [x] Editar css/tablet.css: Agregar media query para ajustar tamaños (max-width 900px, padding/gap reducido, tarjeta más pequeña).
- [x] Editar css/celular.css: Agregar media query para móvil (padding reducido, tamaños de fuente pequeños).

## Dependent Files to be edited
- index.html (agregar HTML).
- css/styles.css (estilos base).
- css/tablet.css (responsividad tablet).
- css/celular.css (responsividad móvil).

## Followup steps
- [x] Verificar visualización: Abrir en navegador para confirmar layout, fondo, tarjeta y responsividad.
- [] Ajustes si necesarios: Si imagen no es correcta o texto cambia, editar.
- [] Pruebas: Interactuar con la sección para asegurar no hay desbordes o errores.
