# Aburto & Montiel Consultores S.A. — Sitio Web V1

Sitio corporativo estático, bilingüe y responsive.

## Publicación recomendada
1. Crear un repositorio GitHub independiente, por ejemplo `am-consultores-web`.
2. Subir el contenido de esta carpeta a la rama `main`.
3. Conectar el repositorio a Cloudflare Pages (Framework preset: None; Build command: vacío; Output directory: `/`).
4. Asociar el dominio corporativo desde Cloudflare Pages > Custom domains.
5. Sustituir en `assets/app.js` el correo temporal `contacto@amconsultores.com` por el correo corporativo real y agregar el número de WhatsApp en formato internacional sin `+`.
6. Añadir el dominio real a metadatos y sitemap cuando quede registrado.

## Pendientes antes de lanzamiento público
- Dominio definitivo.
- Correo corporativo.
- WhatsApp corporativo, si se usará.
- Logotipo definitivo, si existe.
- Fotografías propias o retratos de socios, si se desea sección de equipo.
- Texto legal final de privacidad.
- Integración de analítica solo si la firma la aprueba.

## Arquitectura
- `index.html`: sitio principal.
- `privacidad.html`: aviso de privacidad provisional.
- `assets/styles.css`: diseño responsive.
- `assets/app.js`: navegación, idioma, contacto y configuración.
- `assets/favicon.svg`: icono provisional.
- `assets/og-cover.svg`: imagen social provisional.

## Propuesta agroalimentaria en revisión (web 0.1)
La rama borradores/oferta-agroalimentaria-v0.1 incorpora agroalimentario.html, una tarjeta en Servicios y consultas por modalidad, rubro y destino. Los textos incluyen español e inglés. Véase revision/propuesta-agroalimentaria.md y revision/validacion-agroalimentario.md.

La copia preview/agroalimentario.html se puede descargar y abrir para revisión; no necesita servidor. Su aviso identifica el borrador. El acceso a enlaces del sitio oficial requiere conexión. La nueva página contiene noindex,nofollow. No fusionar a main hasta la aprobación expresa de publicación: el flujo de GitHub Pages puede desplegar esa rama automáticamente.
