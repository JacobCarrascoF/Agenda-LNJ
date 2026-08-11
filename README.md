# Los Niños Jesús · Agenda

App sencilla para llevar la agenda de conciertos de la banda: fecha, ciudad, sala, hoja de ruta (dirección, horas, contacto) y notas del manager. Todo se guarda en el propio dispositivo (localStorage), sin servidor ni base de datos.

## Cómo subirla a GitHub Pages

1. Crea un repositorio nuevo en GitHub (puede ser público o privado).
2. Sube estos archivos a la raíz del repo:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `hand-only.png`
3. En el repo, ve a **Settings → Pages**.
4. En "Source", elige la rama `main` y la carpeta `/ (root)`.
5. Guarda. Al cabo de un minuto tendrás la URL tipo `https://tu-usuario.github.io/nombre-repo/`.

## Cómo instalarla como app en el móvil

- **iPhone (Safari):** abre la URL → botón compartir → "Añadir a pantalla de inicio".
- **Android (Chrome):** abre la URL → menú (⋮) → "Añadir a pantalla de inicio" o "Instalar app".

## Notas

- Los datos se guardan solo en el dispositivo donde se usa. Si queréis que todos los miembros de la banda vean los mismos conciertos, hay que compartir cómo se van añadiendo (por ahora cada uno lo introduce a mano), o pedir una versión con datos compartidos más adelante.
- El diseño usa el logo de la banda (mano rockera) como base del icono y de la marca de agua en la cabecera.
