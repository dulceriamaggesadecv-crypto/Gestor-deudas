# Control de Deudas (PWA)

App para organizar quién te debe, a quién le debés y tus compras en cuotas.
Pensada para instalarse en el celular como una app, usando GitHub Pages
como hosting gratuito.

> **Importante sobre los datos:** esta versión guarda todo en el almacenamiento
> local del navegador/dispositivo (no se sincroniza entre celular y
> computadora). Si borrás los datos del navegador o desinstalás la app,
> perdés la información. No requiere servidor ni base de datos.

## 1. Subir a GitHub

1. Entrá a [github.com](https://github.com) y creá un repositorio nuevo
   (por ejemplo `control-deudas`), público.
2. Subí estos archivos **tal cual están, en la raíz del repositorio**
   (no dentro de una subcarpeta):
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - la carpeta `icons/` completa (con sus 3 imágenes adentro)
   - este `README.md` (opcional)

   Podés hacerlo arrastrando los archivos en la web de GitHub
   ("Add file" → "Upload files") o con git:
   ```bash
   git init
   git add .
   git commit -m "Primera versión de la app"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/control-deudas.git
   git push -u origin main
   ```

## 2. Activar GitHub Pages

1. En el repositorio, andá a **Settings → Pages**.
2. En "Source" elegí **Deploy from a branch**.
3. Elegí la rama **main** y la carpeta **/ (root)**.
4. Guardá. En un minuto o dos, GitHub te va a dar una URL parecida a:
   `https://TU-USUARIO.github.io/control-deudas/`

## 3. Instalar en el celular

**Android (Chrome):**
1. Abrí esa URL en Chrome.
2. Tocá el menú (⋮) → **"Instalar app"** o **"Agregar a pantalla de inicio"**.
3. Confirmá. Va a quedar como un ícono más, se abre en su propia ventana
   sin la barra del navegador.

**iPhone (Safari):**
1. Abrí la URL en Safari (tiene que ser Safari, no Chrome).
2. Tocá el ícono de compartir (el cuadrado con la flecha hacia arriba).
3. Elegí **"Agregar a pantalla de inicio"**.
4. Confirmá. Queda instalada como una app normal.

Una vez instalada, funciona también sin conexión (el service worker
guarda en caché los archivos de la app).

## Actualizar la app más adelante

Si en algún momento querés pedirme cambios o nuevas funciones, hacelo en
el chat como siempre: te vuelvo a generar los archivos actualizados y
solo tenés que volver a subirlos (reemplazar los mismos archivos) al
repositorio de GitHub. GitHub Pages se actualiza solo con cada push.
