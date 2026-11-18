# Banner / Link in bio actualizado

Esta versión incluye:
- fondo negro
- foto de perfil arriba del nombre
- íconos de perfil para cada cuenta de Instagram
- fallback automático a iniciales si alguna imagen no carga

## Publicación en GitHub / Vercel
1. Reemplazá el `index.html` del repo `banner` por este archivo.
2. Hacé commit a `main`.
3. Vercel redeployará automáticamente.

## Si querés cambiar la foto principal
En `index.html`, buscá esta línea:

```html
<img class="hero-avatar" src="https://unavatar.io/instagram/enbuscadeitaca"
```

Si tu Instagram personal es otro, cambiá `enbuscadeitaca` por tu usuario real.
