# Final Fantasy para fanáticos

Proyecto web desarrollado como práctica del curso de Desarrollo Web de Coderhouse.
El sitio reúne información y recursos introductorios sobre la saga Final Fantasy.

## Tecnologías y recursos

- HTML5 con etiquetas semánticas.
- CSS3 para estilos, Flexbox y CSS Grid.
- Diseño responsive con estrategia Mobile First y Media Queries.
- Tipografías Montserrat y Roboto desde Google Fonts.
- Imágenes e iconos guardados en la carpeta `assets/`.

## Estructura del proyecto

```text
Proyecto/
├── index.html
├── pages/
│   ├── contacto.html
│   ├── faq.html
│   ├── proyectos.html
│   ├── servicios.html
│   └── sobre-mi.html
├── styles/
│   └── styles.css
├── assets/
└── README.md
```

## Páginas

- **Inicio:** presentación del sitio y recursos destacados.
- **Sobre mí:** información sobre el creador del proyecto.
- **Servicios:** guías y recursos para los visitantes.
- **Proyectos:** títulos de la saga y contenido relacionado.
- **FAQ:** respuestas a preguntas frecuentes.
- **Contacto:** información y enlaces de contacto.

## Diseño responsive

El diseño parte de una estructura mobile-first: en pantallas pequeñas el contenido se organiza en una columna. A medida que aumenta el ancho de pantalla, las Media Queries adaptan la navegación y las listas.

- **Base móvil:** contenido apilado y listas en una columna.
- **Desde 768 px:** navegación horizontal y listas en dos columnas.
- **Desde 1024 px:** se activan las grillas principales de Inicio y Proyectos; las listas pueden mostrarse en tres columnas.

Se utilizan `display: grid`, `grid-template-areas`, `grid-area`, unidades `fr`, `repeat()`, `minmax()` y `gap`, junto con Flexbox para organizar componentes internos.

## Cómo abrir el proyecto

1. Descargar o clonar el repositorio.
2. Abrir `index.html` en un navegador, por ejemplo Google Chrome.
3. Para probar la responsividad, abrir las herramientas de desarrollador de Chrome y activar la barra de dispositivos (`Ctrl + Shift + M`).

## Convención de nombres

La página “Sobre mí” tiene un único archivo oficial: `pages/sobre-mi.html`. Los enlaces de navegación de todas las páginas apuntan a ese nombre. No se incluye un archivo duplicado llamado `sobremi.html`.

## Autor

Tomás Onetto — Estudiante de Desarrollo Web.


## Integración de Bootstrap (Pre-entrega)

- Bootstrap 5.3.3 se incorpora mediante CDN en todas las páginas: CSS en el `<head>` y `bootstrap.bundle.min.js` antes de `</body>`.
- La navegación de todas las páginas utiliza el Navbar responsivo de Bootstrap, con menú hamburguesa para pantallas pequeñas.
- En `index.html` se agregó un Carousel como galería de imágenes.
- En `pages/proyectos.html` se agregaron Cards y un Modal.
- Se conservaron los layouts originales realizados con Flexbox y CSS Grid.
- Se agregaron estados `:hover`, `:focus` y `:active`, con transiciones suaves, para mejorar la interacción y la accesibilidad.

**Nota sobre el alcance:** el ZIP recibido contiene `index.html` y cinco páginas dentro de `pages/` (Sobre mí, Servicios, Proyectos, FAQ y Contacto). Para no eliminar contenido del proyecto, se actualizó la navbar en los seis archivos HTML.
