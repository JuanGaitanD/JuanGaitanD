# HANDOFF

## Dónde estamos

README bilingüe, banner y foto de perfil.

## Lo que sigue

- Cuando existan los subdominios de `juandgaitan.com` para las demos de open source, agregarlos a la tabla.

## Decisiones

- Sin teléfono en el README: un perfil público lo expone a scraping.
- Etiquetas: SVG propios generados con la paleta Glacial y los iconos del portafolio (chips del stack, encabezados de sección, píldoras de redes e idioma). Reemplazan a skillicons.dev y shields.io, que dejaban n8n vacío y dependían de terceros. Los SVG se generaron con un script fuera del repo; cada tecnología es un SVG en `assets/stack/` (un chip por archivo, para que fluyan al ancho de la pantalla); para agregar una hay que generar su chip.
- Cal.com va solo en el portafolio, no en el README.
- Foto: retrato editado con Nano Banana 2.1, recortado en círculo (`assets/profile.png`, 480 px, esquinas transparentes para que se vea igual en ambos temas de GitHub).
- Stack con variante por tema: chips y encabezados tienen versión clara en `assets/stack/light/` y `assets/labels/light/` (paleta Glacial día), cargadas con `<picture>` y `prefers-color-scheme`. Se descartó dejar los encabezados oscuros en tema claro. Redes e idioma siguen oscuros en ambos temas.
