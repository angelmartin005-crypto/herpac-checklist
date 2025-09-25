
# Herpac – TD360º (Checklist 360º)

Este ZIP está listo para subir a Netlify. Respeta el **master de estilo (Bloque 1)** y mantiene slots para pegar **los 4 bloques validados** sin alterarlos.

## Estructura
- `checklist.html` → formulario único con 4 bloques (multi-step).
- `gracias.html` → página de confirmación.
- `assets/styles.css` → hoja de estilo global validada (color, tipografía, márgenes).
- `assets/img/logo_td.svg`, `assets/img/logo_herpac.svg` → **placeholders** (sustituir por los logos oficiales validados).
- `_redirects` y `netlify.toml` → navegación limpia en Netlify.

## Para finalizar en 3 pasos
1) **Pega los bloques validados** en `checklist.html` donde indican los comentarios `<!-- PEGAR_BLOQUE_X_HTML_VALIDADO_AQUI -->` (no cambies estructura ni clases).
2) **RGPD**: inserta el texto aprobado en el bloque 4, bajo el comentario `<!-- PEGAR_TEXTO_RGPD_VALIDADO_AQUI -->`.
3) **Formspree**: sustituye `FORMSPREE_ACTION_URL_AQUI` por la URL de tu endpoint y cambia el `_redirect` por tu dominio Netlify (p.ej. `https://vocal-kitten-f41905.netlify.app/gracias.html`).

> Nota: mientras no configures Formspree, el envío simula éxito y te lleva a `gracias.html` para pruebas.

## Logos
- Reemplaza los SVG por los **logos oficiales validados** manteniendo posiciones: **izquierda y derecha del título** en header y en el pie del formulario.
