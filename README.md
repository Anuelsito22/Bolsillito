# Bolsillo

App de finanzas personales en un solo archivo, lista para GitHub Pages. Funciona sin conexión después de abrirla una vez.

## Archivos

- `index.html`: la app completa (HTML, CSS y JavaScript).
- `manifest.webmanifest`: nombre, colores e iconos para instalarla.
- `sw.js`: guarda la app en el teléfono para usarla sin conexión.
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`: iconos.

## Publicarla en GitHub Pages

1. Crea un repositorio nuevo en github.com (público si tu plan es el gratuito).
2. Entra al repositorio, toca "uploading an existing file" y sube todos los archivos de esta carpeta. Tienen que quedar en la raíz, no dentro de otra carpeta.
3. Ve a Settings, Pages. En "Build and deployment" elige "Deploy from a branch", rama `main`, carpeta `/ (root)`, y guarda.
4. Espera uno o dos minutos. La dirección será `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Instalarla en el iPhone

1. Abre esa dirección en Safari.
2. Toca Compartir y luego "Agregar a inicio".
3. Ábrela desde el icono. A partir de ahí funciona también sin conexión.

Los datos se guardan en el teléfono, dentro de la app instalada. Para pasarlos desde otro lugar usa Ajustes, Copia de seguridad.

## Actualizar la app

Sube el `index.html` nuevo y cambia el número de versión en la primera línea de código de `sw.js` (`bolsillo-1.3.0`). Así el teléfono descarga la versión nueva.
