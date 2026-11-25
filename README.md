# Thy Cøvenant – thycovenantmusic.com

Sitio web de Thy Cøvenant hecho con Astro y publicado en Vercel.

## Dónde está cada cosa

- `src/pages/index.astro` – el contenido de la página (textos, enlaces, canciones).
- `src/styles/global.css` – el diseño (colores, tipografía, espacios).
- `public/` – imágenes, logo e ícono de la pestaña.
- `src/config.mjs` – aquí se pega el ID del formulario de HighLevel.

## Formularios de correo

El formulario "Join the Circle" se conecta con HighLevel. Cuando el formulario exista en la sub-cuenta de HighLevel, pega su ID en `src/config.mjs` (lo que va después de `/widget/form/` en el enlace del formulario). Mientras esté vacío, la página no muestra formulario y en su lugar invita a seguir a Thy Cøvenant en Spotify.

## Cómo publicar cambios

Cualquier cambio que se suba a este repositorio en GitHub se publica solo en Vercel en un minuto aproximadamente.

## Configuración en Vercel

Vercel detecta Astro automáticamente. No hay que cambiar nada: Build Command `astro build`, Output Directory `dist`.
