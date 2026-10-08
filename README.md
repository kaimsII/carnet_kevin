# Carné virtual

Sitio estático, sin dependencias ni servicios de pago, diseñado para publicarse en GitHub Pages.

## Publicar en GitHub Pages

1. Sube estos archivos a la rama `main` de un repositorio de GitHub.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment → Source**, selecciona **GitHub Actions**.
4. El flujo de trabajo desplegará el sitio automáticamente al subir cambios a `main`. También puedes iniciarlo manualmente desde **Actions → Deploy static site to GitHub Pages → Run workflow**.

La página estará disponible en `https://<usuario>.github.io/<repositorio>/` (o en `https://<usuario>.github.io/` si el repositorio es el sitio personal principal).

## Personalizar los datos

Edita el nombre, los identificadores y el programa en `index.html`. El reloj y la fecha se actualizan automáticamente con la hora local del visitante.

Para cambiar el retrato, pulsa el icono de cámara sobre la imagen y selecciona un archivo de imagen de tu dispositivo. La vista previa es local al navegador y no sube la foto al repositorio; se pierde al recargar la página.
