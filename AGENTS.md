# AGENTS.md

## Propósito

README de perfil de GitHub de Juan David Gaitán (`JuanGaitanD/JuanGaitanD`). GitHub lo muestra en https://github.com/JuanGaitanD. Presenta a Juan como arquitecto de software y cofundador de HYVENTO, y apoya el SEO de https://juandgaitan.com/.

## Archivos

- `README.md`: perfil completo en español (visible) y en inglés (dentro de un `<details>` plegado al final), con el mismo contenido.
- `assets/header.svg`: banner propio con fondo opaco (paleta Glacial del portafolio), legible con el tema claro y el oscuro de GitHub.

## Fuente de verdad

El contenido sale del repositorio del portafolio (`src/content/es.ts`, `en.ts`, `shared.ts`) y los colores de `src/app/globals.css`. No se inventan logros, cifras ni tecnologías. Un dato sin confirmar se le pregunta a Juan. Cualquier cambio de datos se hace en las dos versiones del README.

## Convenciones

- Idioma: español neutro visible, inglés en el desplegable `<details id="english">`, mismo contenido. Un cambio de datos se hace en las dos versiones.
- Sin rayas largas, sin antítesis del tipo "no es X, es Y", sin adverbios de refuerzo ni relleno.
- Sin tarjetas de estadísticas de terceros (github-readme-stats, streak-stats y similares).
- Etiquetas de redes e idioma: SVG propios en `assets/social/` y `assets/lang/`, con el estilo de los botones del portafolio (Simple Icons y Lucide). Sin servicios de terceros como skillicons.dev o shields.io.
- Stack: un SVG animado por idioma y tema en `assets/stack-anim/{es,en}-{dark,light}.svg` (CSS puro, ciclo de 14 s, lienzo de 440 px para que se lea en móvil), cargado con `<picture>` según el tema de GitHub. Respeta `prefers-reduced-motion`. No puede arrancar al entrar en la sección: un SVG dentro de `<img>` no tiene detector de scroll.
- Todo `<img>` lleva `alt` descriptivo. El primer encabezado visible incluye "Juan David Gaitán".
- Commits en Conventional Commits, en español.

## Qué no tocar

- La configuración del perfil de GitHub (bio, nombre, enlaces) ni el repositorio del portafolio.
- No agregar GitHub Actions ni dependencias.
- Sin teléfono en el README.
