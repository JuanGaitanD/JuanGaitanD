# AGENTS.md

## Propósito

README de perfil de GitHub de Juan David Gaitán (`JuanGaitanD/JuanGaitanD`). GitHub lo muestra en https://github.com/JuanGaitanD. Presenta a Juan como arquitecto de software y cofundador de HYVENTO, y apoya el SEO de https://juandgaitan.com/.

## Archivos

- `README.md`: perfil completo en español y en inglés, con el mismo contenido.
- `assets/header.svg`: banner propio con fondo opaco (paleta Glacial del portafolio), legible con el tema claro y el oscuro de GitHub.

## Fuente de verdad

El contenido sale del repositorio del portafolio (`src/content/es.ts`, `en.ts`, `shared.ts`) y los colores de `src/app/globals.css`. No se inventan logros, cifras ni tecnologías. Un dato sin confirmar se le pregunta a Juan. Cualquier cambio de datos se hace en las dos versiones del README.

## Convenciones

- Idioma: español neutro primero, inglés después, mismo contenido.
- Sin rayas largas, sin antítesis del tipo "no es X, es Y", sin adverbios de refuerzo ni relleno.
- Sin tarjetas de estadísticas de terceros (github-readme-stats, streak-stats y similares).
- Etiquetas (stack, encabezados de sección, redes, idioma) como SVG propios en `assets/stack/`, `assets/labels/`, `assets/social/` y `assets/lang/`, con el estilo de los chips y botones del portafolio y sus iconos (Simple Icons y Lucide). Chips y encabezados del stack tienen variante clara en `light/` (Glacial día) y se cargan con `<picture>` según el tema de GitHub. Sin servicios de terceros como skillicons.dev o shields.io.
- Todo `<img>` lleva `alt` descriptivo. El primer encabezado visible incluye "Juan David Gaitán".
- Commits en Conventional Commits, en español.

## Qué no tocar

- La configuración del perfil de GitHub (bio, nombre, enlaces) ni el repositorio del portafolio.
- No agregar GitHub Actions ni dependencias.
- Sin teléfono en el README.
