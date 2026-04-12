# Mr. Furry PWA — Instrucciones de despliegue

## Archivos incluidos
- `index.html` — la app completa
- `manifest.json` — configuración PWA (nombre, icono, colores)
- `sw.js` — service worker (funciona offline, instalable)
- `icon-192.png` — icono app (añadir manualmente)
- `icon-512.png` — icono app grande (añadir manualmente)

## Iconos
Necesitas crear dos iconos PNG con el logo de Mr. Furry:
- `icon-192.png` → 192×192px
- `icon-512.png` → 512×512px

Puedes generarlos en https://realfavicongenerator.net o con cualquier herramienta de diseño.

## Despliegue en Netlify (recomendado, gratis)
1. Ve a https://app.netlify.com
2. Crea una cuenta gratuita
3. Arrastra la carpeta entera a "Deploy manually"
4. En segundos tienes una URL tipo `mrfurry.netlify.app`
5. Puedes conectar tu dominio propio (misterfurry.com) desde Settings > Domain management

## Despliegue en Vercel (alternativa)
1. Ve a https://vercel.com
2. Instala Vercel CLI: `npm i -g vercel`
3. Desde la carpeta del proyecto: `vercel --prod`

## Hacer que sea instalable en el móvil
Una vez subida:
- **Android**: al abrir la web en Chrome aparece un banner "Añadir a pantalla de inicio"
- **iPhone**: en Safari > botón compartir > "Añadir a pantalla de inicio"

## Próximos pasos
- Sustituir los iconos placeholder por el logo real
- Conectar el checkout con Shopify (sustituir la pantalla de pago por Shopify Buy Button o Storefront API)
- Añadir Google Analytics para seguimiento
- Configurar dominio propio
