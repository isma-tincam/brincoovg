# Espiral Nova

Shooter arcade espacial en HTML, CSS y JavaScript nativos. Es un sitio estático: no necesita OpenAI Sites, servidor de aplicación, dependencias ni proceso de build. La nave se carga desde `sites/espiral-nova/dist/assets/player-ship.png`.

## Ejecutarlo localmente

Desde la raíz del repositorio, ejecuta:

`python -m http.server 8000 --directory sites/espiral-nova/dist`

Luego abre `http://localhost:8000`. También puedes servir esa carpeta con cualquier servidor estático.

## Publicarlo con GitHub Pages

El workflow `.github/workflows/deploy-espiral-nova.yml` publica automáticamente `sites/espiral-nova/dist` al hacer push a la rama `juegos`. Para habilitarlo, en **Settings → Pages**, selecciona **GitHub Actions** como fuente.
