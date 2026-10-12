# HANDOFF

## Dónde estamos

README bilingüe, banner y foto de perfil.

## Lo que sigue

- Cuando existan los subdominios de `juandgaitan.com` para las demos de open source, agregarlos a la tabla.

## Decisiones

- Sin teléfono en el README: un perfil público lo expone a scraping.
- Etiquetas de redes e idioma: SVG propios con la paleta Glacial y los iconos del portafolio. Reemplazan a skillicons.dev y shields.io, que dependían de terceros y dejaban n8n vacío. Se generaron con un script fuera del repo.
- Cal.com va solo en el portafolio, no en el README.
- Foto: retrato editado con Nano Banana 2.1, recortado en círculo (`assets/profile.png`, 480 px, esquinas transparentes para que se vea igual en ambos temas de GitHub).
- Stack: SVG estático en terminal, en tres anchos (440, 640 y 860 px) y dos temas, elegidos con `<picture>`. Se probó una animación (CSS puro, ciclo de 14 s) y se retiró: en Chrome corre aunque la imagen no esté a la vista, así que no podía arrancar al entrar en la sección. Sigue en el historial de git (commit 3d067a9).
- Modo claro: banner, píldoras de redes e idioma y stack tienen variante Glacial día. Riesgo conocido: GitHub envuelve el `<picture>` en `themed-picture`; con consultas combinadas (`min-width` y `prefers-color-scheme`) sin probar en vivo, si el tema de GitHub difiere del del sistema puede mostrar la variante del sistema.
- README más corto: español visible, inglés en `<details id="english">` al final. GitHub no abre el desplegable con un ancla, así que el botón EN de la cabecera lleva al desplegable y se abre con un clic.
