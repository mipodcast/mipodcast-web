# Guía de Edición para mipodcast.cl

## Cómo editar el contenido de tu página web

### 1. Cambiar los videos de YouTube

Para cambiar los videos en la galería de la página Home:

1. Abre el archivo `index.html`
2. Busca las líneas que contienen `src="https://www.youtube.com/embed/dQw4w9WgXcQ"`
3. Reemplaza `dQw4w9WgXcQ` con el ID del video de YouTube que quieres mostrar
   - El ID del video es la parte que aparece después de `v=` en la URL de YouTube
   - Por ejemplo, si tu video es `https://www.youtube.com/watch?v=ABC123XYZ`, el ID es `ABC123XYZ`

### 2. Cambiar las descripciones de los videos

Para cambiar el texto debajo de cada video:

1. Abre el archivo `index.html`
2. Busca las líneas que contienen `<p class="video-description">`
3. Cambia el texto entre las etiquetas `<p>` y `</p>`

### 3. Editar los textos de servicios

Para cambiar las descripciones de los servicios:

1. Abre el archivo `index.html`
2. Busca las líneas que contienen `<p class="service-description">`
3. Modifica el texto según tus necesidades

### 4. Cambiar las fotos del equipo

Para reemplazar las fotos del equipo:

1. Guarda tus fotos con los nombres: `team1.jpg`, `team2.jpg`, `team3.jpg`
2. Reemplaza los archivos existentes en la carpeta del proyecto
3. Las fotos deben ser cuadradas para mejor visualización

### 5. Editar las biografías del equipo

Para cambiar los nombres y biografías:

1. Abre el archivo `index.html`
2. Busca las secciones con `<h3>Nombre del Miembro X</h3>`
3. Cambia los nombres y las biografías en las etiquetas `<p class="team-bio">`

### 6. Cambiar el logo

Para reemplazar el logo:

1. Guarda tu nuevo logo como `logo.png`
2. Reemplaza el archivo existente en la carpeta del proyecto

### 7. Cambiar los iconos de servicios

Para reemplazar los iconos de servicios:

1. Guarda tus nuevos iconos como: `icon-video.png`, `icon-photo.png`, `icon-podcast.png`
2. Reemplaza los archivos existentes en la carpeta del proyecto

## Estructura de archivos

- `index.html` - Archivo principal con todo el contenido
- `styles.css` - Estilos y diseño de la página
- `script.js` - Funcionalidad de navegación
- `logo.png` - Logo de la productora
- `icon-video.png` - Icono del servicio de video
- `icon-photo.png` - Icono del servicio de fotografía
- `icon-podcast.png` - Icono del servicio de podcast
- `team1.jpg`, `team2.jpg`, `team3.jpg` - Fotos del equipo

## Notas importantes

- Todos los textos están en español
- La página es completamente responsive (se adapta a móviles)
- Los enlaces de contacto en el pie de página ya están configurados
- Para subir la página a GitHub Pages, sube todos estos archivos a un repositorio de GitHub

