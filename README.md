# Control de Deudas (PWA)

Esta carpeta contiene la aplicación y los archivos necesarios para publicarla como una aplicación web instalable (PWA) en GitHub Pages.

## Publicar la versión actualizada

1. Abre el repositorio `https://github.com/dulceriamaggesadecv-crypto/Gestor-deudas`.
2. Entra a la pestaña **Code**.
3. Usa **Add file → Upload files**.
4. Descomprime este ZIP en tu computadora/celular y sube los archivos y la carpeta `icons` a la **raíz** del repositorio. Deben quedar así:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
   - `icons/apple-touch-icon.png`
5. Si GitHub pregunta si deseas reemplazar archivos existentes, confirma para estos archivos. No borres otros archivos del repositorio.
6. Pulsa **Commit changes** y espera uno o dos minutos a que GitHub Pages publique los cambios.

## Instalar en Android

1. Abre la página en Google Chrome: `https://dulceriamaggesadecv-crypto.github.io/Gestor-deudas/`.
2. Recarga la página. Si no cambia, cierra la pestaña y vuelve a abrir el enlace.
3. Pulsa el menú ⋮ de Chrome y busca **Instalar aplicación**. Si aparece, selecciónalo y confirma.
4. Si Chrome aún dice que no se puede instalar, abre el enlace en una pestaña normal de Chrome (no en un navegador integrado) y revisa que el sitio haya terminado de cargar con conexión a internet.

## Importante sobre tus datos

La aplicación guarda los registros en el almacenamiento local del navegador/dispositivo. No se sincronizan con otros dispositivos. Antes de borrar datos de Chrome o desinstalar, conserva cualquier registro importante por separado.

Esta actualización cambia solo la configuración PWA y la caché, no la lógica de registro de deudas.
