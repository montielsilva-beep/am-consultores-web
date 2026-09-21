# Aburto & Montiel Consultores S.A. — Sitio corporativo V1

Sitio web estático, bilingüe y responsive preparado para despliegue desde GitHub.

## Estructura
- `index.html` — sitio principal
- `privacidad.html` — aviso de privacidad provisional
- `assets/styles.css` — estilos
- `assets/app.js` — interacción, idioma y formulario
- `assets/favicon.svg` — favicon
- `assets/og-cover.svg` — imagen Open Graph
- `robots.txt` — rastreo básico

## Antes de producción
1. Sustituir en `assets/app.js` el correo temporal `contacto@amconsultores.com` por el correo corporativo real y agregar el número de WhatsApp en formato internacional sin `+`.
2. Revisar el aviso de privacidad con datos societarios/contacto definitivos.
3. Definir dominio corporativo y actualizar metadatos/canonical si procede.
4. Configurar un servicio de formularios o backend si se desea recepción directa desde el formulario web.

## Despliegue
La raíz del sitio es este directorio: `index.html` debe permanecer en la raíz del repositorio. Es apto para GitHub Pages, Cloudflare Pages u otro hosting estático.
