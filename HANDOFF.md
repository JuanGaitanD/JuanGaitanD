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
- Stack animado: un SVG por idioma y tema (`assets/stack-anim/`), con el guiño `$ ls tech-stack/` que despliega cada categoría. Sustituye a los chips sueltos y a los encabezados. Lienzo de 440 px para minimizar la reducción en móvil. Se verificó en Chrome que la animación corre aunque la imagen no esté a la vista, así que no puede arrancar al entrar en la sección; por eso el ciclo es corto (14 s) y se repite. Sin probar en Safari ni Firefox.
- README más corto: español visible, inglés en `<details id="english">` al final. GitHub no abre el desplegable con un ancla, así que el botón EN de la cabecera lleva al desplegable y se abre con un clic.
