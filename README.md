# Extractor de Imágenes

PWA estática para GitHub Pages. Extrae imágenes desde páginas que permitan solicitudes CORS y genera ZIP directamente en el navegador.

## Publicación
El workflow incluido despliega automáticamente el contenido de `main` en GitHub Pages.

## Importante
GitHub Pages no puede ejecutar backend/serverless ni saltarse CORS. Por eso esta versión realiza todo en el navegador y funciona con sitios que permitan solicitudes CORS.