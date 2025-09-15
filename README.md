Descripción General

La Redonda es una web informativa orientada al fútbol, que presenta noticias, calendarios de partidos y secciones destacadas por país y competición. En esta entrega final, se implementó una estructura modular con HTML semántico, estilos avanzados con SASS/SCSS, diseño responsive con Bootstrap y Flex/Grid, y control de versiones con Git y GitHub.

--////////////////////////////////////////////////////--

Objetivos cumplidos
Estructura final de la web con HTML limpio y semántico

Estilo visual con Bootstrap + SASS

Implementación completa de SASS: variables, mixins, nesting, operadores

Diseño responsive para mobile y desktop

Proyecto versionado en GitHub

Publicación en GitHub Pages

--////////////////////////////////////////////////////--

Estructura HTML
Uso de etiquetas semánticas: <header>, <nav>, <main>, <aside>, <section>, <article>, <footer>

Clases utilitarias de Bootstrap para layout (container, row, col-md-*, navbar, etc.)

Navegación funcional entre páginas: index.html, noticias.html, calendario.html, contacto.html

Imágenes con alt descriptivo y rutas relativas compatibles con GitHub Pages

--////////////////////////////////////////////////////--

Estilo con SASS/SCSS
Migración de estilos desde CSS a SCSS

Uso de:

Variables ($color-fondo, $color-texto, $radio, etc.)

Mixins (@include sombra-suave, @include responsive-form)

Nesting (.seccion h2, .contenido form input, etc.)

Operadores (lighten, darken)

Selectores optimizados con & (&:hover, &::placeholder)

Animaciones y transiciones aplicadas en botones, artículos y elementos destacados

Paleta de colores coherente y contraste visual adecuado

--////////////////////////////////////////////////////--

Estructura de carpetas

PreEntregaMMiranda/
├── index.html
├── html/
│   ├── noticias.html
│   ├── calendario.html
│   ├── contacto.html
│   └── resultado.html
├── estilos/
│   ├── style.scss
│   ├── style.css
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _base.scss
│   ├── _layout.scss
│   └── _components.scss
├── assets/
│   ├── gavi.jpg
│   ├── fichaje.jpg
│   ├── lookman.jpg
│   └── celebracion.jpg
├── .gitignore
└── README.md


--////////////////////////////////////////////////////--

Diseño Responsivo
Layout adaptable en mobile, tablet y desktop

Uso de unidades relativas (rem, %)

Navegación y contenido legible en todos los tamaños

Probado en distintos navegadores y resoluciones

--////////////////////////////////////////////////////--

Buenas prácticas aplicadas
Modularización de estilos con partials SCSS

Reutilización de código con mixins

Separación clara entre estructura, estilo y funcionalidad

Documentación de cambios en commits

Optimización visual y técnica