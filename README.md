# Editorial Escatonomicón — web para GitHub Pages

Esta carpeta contiene una web estática lista para publicar en GitHub Pages.

## Archivos principales

- `index.html`: página principal.
- `styles.css`: estilos visuales.
- `script.js`: menú móvil y año automático.
- `assets/`: imágenes SVG de la identidad visual.
- `pdfs/`: coloca aquí tus PDFs descargables.

## Cómo publicarla gratis en GitHub Pages

1. Crea una cuenta en GitHub, si todavía no la tienes.
2. Crea un repositorio nuevo llamado `editorial-escatonomicon`.
3. Sube todos los archivos de esta carpeta al repositorio.
4. Entra en `Settings` > `Pages`.
5. En `Build and deployment`, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Guarda los cambios.
7. La web aparecerá en una dirección similar a:

   `https://TU_USUARIO.github.io/editorial-escatonomicon/`

## Para usar una dirección principal

Si quieres que la web esté en:

`https://TU_USUARIO.github.io/`

crea el repositorio con el nombre exacto:

`TU_USUARIO.github.io`

y sube ahí estos archivos.

## Sustituir PDFs

Cambia los archivos de la carpeta `pdfs/` por los PDFs reales y conserva estos nombres si no quieres tocar el HTML:

- `rituales-en-la-lluvia.pdf`
- `ficha-personaje.pdf`
- `erratas.pdf`

También puedes cambiar los enlaces directamente en `index.html`.

## Foro

GitHub Pages no ejecuta foros internos con usuarios y base de datos. La opción gratuita recomendada es:

- GitHub Discussions, si quieres mantenerlo todo en GitHub.
- Discord, si quieres una comunidad más viva.
- Google Groups, si quieres algo más sencillo y clásico.

En `index.html` busca `TU_USUARIO` y sustitúyelo por tu usuario real de GitHub.


## Cambios visuales realizados

- Se ha insertado de forma visible el logo/sigilo de la editorial en la cabecera y en el bloque principal.
- Se ha añadido una tipografía gótica para títulos, botones, navegación y marca mediante Google Fonts (`UnifrakturCook`).
- El cuerpo del texto mantiene una serif legible (`Cormorant Garamond`) para no perjudicar la lectura.
