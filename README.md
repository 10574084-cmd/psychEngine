# Psych Engine Web Lite

Prototipo experimental para navegador, no es el motor nativo completo de Psych Engine.

## Publicar en GitHub Pages
1. Sube también la carpeta `assets/` del paquete Lite (charts JSON e instrumentales OGG).
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. Abre la URL de Pages que GitHub te muestre.

## Importante
Este repositorio contiene la interfaz web y el cargador. Para que las canciones funcionen deben estar disponibles `songs.json` y los archivos de `assets/` con las mismas rutas. El ZIP Lite de 33 MB no se puede adjuntar mediante el editor de archivos de texto de GitHub; hay que subir su contenido desde la interfaz web de GitHub. No se trata de una conversión completa del motor: scripts Lua, personajes animados y muchas funciones nativas no están portados.