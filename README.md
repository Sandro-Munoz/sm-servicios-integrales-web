# SM Servicios Integrales SpA — Sitio web corporativo

Sitio estático sin dependencias, preparado para GitHub y Cloudflare Pages.

## Publicación
1. Crear repositorio público en GitHub, por ejemplo `sm-servicios-integrales-web`.
2. Cargar los archivos `index.html`, `README.md` y la carpeta `assets` (con `logo-sm.jpg`) a la raíz del repositorio.
3. En Cloudflare: **Workers & Pages → Create → Pages → Connect to Git**. Seleccionar el repositorio de GitHub.
4. Framework preset: **None**; Production branch: `main`; Build command: `exit 0`; Build output directory: `/` (raíz del repositorio).
5. Publicar. Cloudflare asignará una URL del tipo `nombre-proyecto.pages.dev`.

## Configuración
- Teléfono comercial: +56 9 6675 8426.
- Los botones de WhatsApp abren una conversación; no envían información automáticamente.
- Sustituir los textos o imágenes según evolución de los servicios.
- La imagen del logotipo proviene de la referencia aportada por el dueño y está recortada; podrá sustituirse por archivo vectorial/transparente de mayor calidad cuando esté disponible.

No se requiere instalar Node.js, ni pagar servicios de base de datos, ni configurar variables secretas.
