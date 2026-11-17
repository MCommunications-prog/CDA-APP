# App CDA Casa del Alfarero

Web app instalable (PWA) de la Iglesia de Dios CDA Orlando. Gratis, publicada con GitHub Pages.

## Cambiar contenido
Todo está en `index.html`. Los eventos especiales se agregan en la lista `EVENTOS` (busca "const EVENTOS").
Después de cambiar algo, sube el número en `sw.js` (`cda-v1` → `cda-v2`) para que los teléfonos tomen la versión nueva.

## Instalar en el celular
- **Android (Chrome):** abre el enlace → menú ⋮ → "Instalar app" o "Agregar a pantalla principal".
- **iPhone (Safari):** abre el enlace → botón Compartir → "Agregar a pantalla de inicio".

## Google Play (más adelante, $25 una sola vez)
1. Entra a https://www.pwabuilder.com y pega el enlace de la app.
2. Elige "Package for stores" → Android. Descarga el paquete (.aab) y el archivo `assetlinks.json`.
3. Sube `assetlinks.json` a la carpeta `.well-known/` de este repositorio.
4. Crea la cuenta de Google Play Console y sube el .aab.
