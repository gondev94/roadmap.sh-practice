# roadmap.sh — práctica de HTML

Prácticas de HTML semántico, sin CSS. El diseño queda para el proyecto de estilos.

## Cómo verlo

Abre el HTML en el navegador. No hace falta instalar nada ni levantar un servidor.

## Sitio de varias páginas

Sitio con inicio, proyectos, artículos, about y contacto. La misma barra de navegación está en todas las páginas.

- **Header:** nombre, rol y navegación.
- **Main:** en inicio, presentación, listas de proyectos, artículos y educación. En el resto, el detalle de esa sección.
- **Footer:** contacto y copyright.
- **Contacto:** formulario con nombre, correo, asunto y mensaje.

Metaetiquetas en cada página: `title`, `description`, `author`, `keywords` y Open Graph (`og:title`, `og:description`, `og:type`).

Archivos:

- `HTML/index.html` — inicio.
- `HTML/projects.html` — proyectos.
- `HTML/articles.html` — artículos.
- `HTML/about.html` — perfil y foto.
- `HTML/contact.html` — formulario de contacto.
- `HTML/foto-cv-web.webp` — foto de la página About.
- `HTML/favicon-32x32.png` — icono de la pestaña.

Proyecto: [Sitio web HTML básico](https://roadmap.sh/projects/basic-html-website)

## CV de una página

Currículum en un solo HTML. Cabecera con nombre y contacto, skills, educación y experiencia. Cada formación y cada proyecto van en su propio `article`.

- `HTML/single-page-cv.html` — la página del CV.

Proyecto: [Single Page CV](https://roadmap.sh/projects/single-page-cv)

## Tabla de comparación de precios

Página de una sola tabla que compara planes de suscripción. Sin CSS: la estructura y la accesibilidad de la tabla son el objetivo.

- **Header:** marca y navegación.
- **Main:** título y tabla de planes (Free, Pro y Business) con almacenamiento, proyectos y soporte.
- **Footer:** copyright.
- **Tabla:** `caption`, `thead` y `tbody`. Los encabezados de columna usan `scope="col"` y el nombre de cada plan usa `scope="row"`. Una fila con `colspan` indica que todos los planes incluyen SSL y copias diarias.

- `HTML/pricin-comparison-table.html` — la página de la tabla.

Proyecto: [Pricing Comparison Table](https://roadmap.sh/projects/pricing-comparison-table)

## Entrada de blog

Dos páginas de artículo, sin CSS. El objetivo es elegir la etiqueta según el significado del texto.

- **Header:** nombre del sitio y navegación.
- **Main:** título, fecha, párrafos, lista, cita, ejemplo de código y un enlace para seguir leyendo.
- **Figure:** imagen con `alt` y `figcaption`.
- **Footer:** copyright.
- **Head:** `title`, `charset`, `viewport` y una `description` que resume la publicación.

- `HTML/blog-post-page.html` — publicación sobre HTML semántico.
- `HTML/blog.html` — publicación sobre esports y Counter-Strike.
- `HTML/mountain-icon-simple-thin-outline_1223784-3557.avif` — imagen del artículo de HTML semántico.
- `HTML/images.jpg` — imagen del artículo de Counter-Strike.

Proyecto: [Semantic HTML](https://roadmap.sh/projects/blog-post-page)


## Formulario de contacto

Página de soporte de Acme, sin CSS y sin JavaScript. El objetivo es el formulario que el navegador convierte en una petición: cada control tiene `name`, una etiqueta asociada y la validación nativa.

- **Header:** marca y navegación (Home, Help, Contact).
- **Main:** título, una frase y el formulario.
- **Formulario:** `action` con una URL de marcador y `method="post"`. Nombre y correo obligatorios, asunto en un `select` con tres opciones, mensaje en un `textarea` con `minlength`, radios dentro de un `fieldset` con `legend` y un checkbox opcional de novedades.
- **Footer:** copyright.
- **Head:** `title`, `charset` y `viewport`.

- `HTML/contacform.html` — la página del formulario.

Proyecto: [Contact Form](https://roadmap.sh/projects/contact-form)
## Repositorio

## Colección de fotos

Página de una colección sobre café, sin CSS. El objetivo es el marcado que decide cómo se carga, se describe y se anuncia el contenido multimedia.

- **Header:** título, una frase y un icono decorativo con `alt=""`.
- **Main:** seis fotos. Cada `img` tiene `src`, `alt`, `width` y `height`. Tres van dentro de `figure` con `figcaption`.
- **Video:** `controls`, `poster` y un texto de reserva por si el navegador no reproduce el archivo.
- **Footer:** la sección está presente, sin texto.
- **Head:** `title`, `charset` y `viewport`, además de `description`, `author`, `keywords` y Open Graph.

Archivos:

- `HTML/photoshowcase.html` — la página.
- `HTML/cafe01.jpg`, `HTML/cafe02.jpg`, `HTML/cafe03.jpg`, `HTML/cafe04.jpg`, `HTML/cafe05.jpg` y `HTML/cafe05.png` — las fotos.
- `HTML/cafecito-video.mp4` — el vídeo.
- `HTML/favicon-32x32.png` — icono decorativo y de la pestaña.

Proyecto: [Photo Showcase](https://roadmap.sh/projects/photo-showcase)

[github.com/gondev94/roadmap.sh-practice](https://github.com/gondev94/roadmap.sh-practice)
