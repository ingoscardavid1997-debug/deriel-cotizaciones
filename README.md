# Deriel Cotizaciones (PWA)

Aplicación independiente de Deriel Control.

## Publicar en GitHub Pages
1. Crear un repositorio público llamado `deriel-cotizaciones`.
2. Subir todos los archivos y carpetas de este paquete a la raíz del repositorio.
3. En GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Esperar a que GitHub Pages publique el sitio.

Dirección esperada:
https://ingoscardavid1997-debug.github.io/deriel-cotizaciones/

## Instalar
- Android: abrir la dirección en Chrome → menú ⋮ → Instalar aplicación / Añadir a pantalla principal.
- PC: abrir en Chrome o Edge → icono Instalar en la barra de direcciones.

## Funcionamiento sin conexión
El service worker almacena la app shell. Las cotizaciones se guardan en el almacenamiento local del navegador/dispositivo; no se sincronizan entre dispositivos.

## Nota
El QR y el logo están embebidos en `index.html`. El service worker cachea la aplicación. La primera visita necesita conexión para descargarla.
