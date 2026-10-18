CodePOS MX — Sitio web estático

Estructura
- index.html: página principal.
- nfc.html: productos y soluciones NFC/QR.
- catalogo.html: catálogo de productos y servicios.
- styles.css: estilos de la página principal y del catálogo.
- nfc.css: estilos de la página NFC/QR.
- public/: imágenes y favicon de marca.

Revisión local
1. Abre una terminal en esta carpeta.
2. Ejecuta: python3 -m http.server 8000
3. Visita http://localhost:8000/ y revisa index.html, nfc.html y catalogo.html.
4. Detén el servidor con Ctrl+C.

Publicación en GitHub Pages
1. Usa la copia del repositorio correcto y conserva esta estructura de carpetas.
2. Añade y sube los archivos HTML, CSS y public/ a la rama publicada.
3. En Settings > Pages, selecciona la rama y la carpeta raíz correspondientes.
4. Verifica las tres páginas después de publicar:
   - /CodePOSMX-page/
   - /CodePOSMX-page/nfc.html
   - /CodePOSMX-page/catalogo.html

El sitio no incluye un backend ni procesamiento de pagos. No publiques el instalador
del software POS ni credenciales en el repositorio o en GitHub Pages.

Poppins se carga desde Google Fonts y requiere conexión a internet. Los canales de
contacto configurados son el correo y las redes sociales existentes; el número de
WhatsApp comercial queda pendiente.
