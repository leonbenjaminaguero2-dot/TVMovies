# TVMovies Admin — iOS

Aplicación iOS con Capacitor que abre **https://admintvmovies.netlify.app/** dentro de una WebView.

## Desde GitHub (sin Mac)

1. Crear un repositorio **privado** (por ejemplo `TVMoviesAdmin-iOS`).
2. Descomprimir este ZIP y subir **el contenido** a la raíz del repositorio, incluida la carpeta oculta `.github`.
3. Ir a **Actions → TVMovies Admin - IPA → Run workflow**.
4. Al terminar en verde, abrir **Artifacts → TVMoviesAdmin-IPA**, descargar el ZIP de GitHub y extraer `TVMoviesAdmin-unsigned.ipa`.
5. La IPA no está firmada: el instalador debe firmarla correctamente antes de instalarla.

## Notas

- La página se carga en línea: necesita Internet y que Netlify esté disponible.
- El sitio remoto debe tener su propia autenticación segura; que el repositorio sea privado no protege el panel web.
- La sesión web utiliza el almacenamiento persistente normal de WKWebView; la duración depende también del servidor.
- Algunas funciones del navegador (ventanas emergentes, descargas, permisos especiales) podrían necesitar adaptaciones.
- No se publica ni modifica la web desde este proyecto.
