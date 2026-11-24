Proyecto Final Fantasy

Ver sitio web publicado

Sitio multipágina sobre la saga Final Fantasy, realizado como práctica del curso de Desarrollo Web.

Tecnologías utilizadas

HTML5

CSS3

SCSS

Bootstrap 5.3.3

Google Fonts

Páginas

Inicio

Sobre mí

Servicios

Proyectos

Preguntas frecuentes (FAQ)

Contacto

Organización del proyecto

index.html: página principal.

pages/: páginas internas.

assets/: imágenes.

scss/: archivos SCSS organizados en parciales.

scss/main.scss: archivo principal de SCSS.

styles/styles.css: CSS compilado que utiliza el sitio.

Compilación de SCSS

Instalar las dependencias:

npm install

Compilar los estilos:

npm run sass

Compilar automáticamente al modificar archivos SCSS:

npm run sass:watch

El proyecto utiliza @use para importar los parciales SCSS desde un único archivo principal.

Bootstrap continúa integrado mediante CDN y se conservan los archivos HTML originales.

Objetivo

Practicar la organización de estilos mediante SCSS, el uso de variables, mixins, anidamiento y diseño responsive.