# AGENTS.md

## Propósito

README de perfil de GitHub de Juan David Gaitán (`JuanGaitanD/JuanGaitanD`). GitHub lo muestra en https://github.com/JuanGaitanD. Presenta a Juan como arquitecto de software y cofundador de HYVENTO, y apoya el SEO de https://juandgaitan.com/.

## Archivos

- `README.md`: perfil completo en español (visible) y en inglés (dentro de un `<details>` plegado al final), con el mismo contenido.
- `assets/header.svg` y `assets/header-light.svg`: banner propio en paleta Glacial (oscuro) y Glacial día (claro), cargado con `<picture>` según el tema de GitHub. El grafo de servicios está animado (SMIL y CSS, sin JavaScript) como el de `SectionGraph` del portafolio: las aristas crecen en ángulo recto, los nodos aparecen, viajan mensajes con estela, cada llegada lanza un anillo de pulso y un mensaje falla en rojo, parpadea y reintenta. Con `prefers-reduced-motion` se ve el grafo final sin mensajes. No incluye los easter eggs que dependen de la fecha o del clic (el viernes de `prod`, ping, chaos monkey).

## Fuente de verdad

El contenido sale del repositorio del portafolio (`src/content/es.ts`, `en.ts`, `shared.ts`) y los colores de `src/app/globals.css`. No se inventan logros, cifras ni tecnologías. Un dato sin confirmar se le pregunta a Juan. Cualquier cambio de datos se hace en las dos versiones del README.

## Convenciones

- Idioma: español neutro visible, inglés en el desplegable `<details id="english">`, mismo contenido. Un cambio de datos se hace en las dos versiones.
- Sin rayas largas, sin antítesis del tipo "no es X, es Y", sin adverbios de refuerzo ni relleno.
- Sin tarjetas de estadísticas de terceros (github-readme-stats, streak-stats y similares).
- Etiquetas de redes e idioma: SVG propios en `assets/social/` y `assets/lang/` (variante clara en `light/`), con el estilo de los botones del portafolio (Simple Icons y Lucide) y `<picture>` para el tema. Sin servicios de terceros como skillicons.dev o shields.io.
- Stack: SVG estático por idioma, tema y ancho en `assets/stack/{es,en}-{dark,light}[-mid|-wide].svg`: 440 px (mínimo y móvil), 640 px (viewport desde 800 px) y 860 px (desde 1100 px). Terminal `$ ls tech-stack/` con carpetas y chips, alineada a la izquierda, elegida con `<picture>` (`min-width` y `prefers-color-scheme`). Un SVG dentro de `<img>` no puede medir el ancho del README, por eso son tres tamaños fijos. Se descartó la animación.
- Los SVG de assets se generaron con un script fuera del repo (paleta Glacial y Glacial día del portafolio). Para cambiar su contenido hay que regenerarlos.
- Todo `<img>` lleva `alt` descriptivo. El primer encabezado visible incluye "Juan David Gaitán".
- Commits en Conventional Commits, en español.

## Qué no tocar

- La configuración del perfil de GitHub (bio, nombre, enlaces) ni el repositorio del portafolio.
- No agregar GitHub Actions ni dependencias.
- Sin teléfono en el README.
