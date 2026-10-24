# Inmobiliaria Bapersa — Inversiones

Landing page bilingüe (ES/EN) de Inmobiliaria Bapersa para inversionistas: proyectos activos, mapa interactivo, tabla de inversiones, formulario de inversionistas (WhatsApp + Google Sheets) y formulario de contacto.

## Estructura
- `index.html` — página completa (HTML, CSS y JS en un solo archivo).
- `img/` — fotografías, planos y portadas.

## Editar datos
Al inicio del `<script>` de `index.html`:
- `CONFIG` — WhatsApp, correo, dirección y `sheetsEndpoint` (URL de Google Apps Script que guarda los formularios).
- `PROJECTS` — proyectos, galerías, precios y enlaces (recorrido 360°, sitio web).
- `BEFORE_AFTER`, `PLANS`, `RETURNS` — antes/ahora, planos y tabla de inversiones.

## Publicar con GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
