# Yincanas

Aplicación sencilla para crear preguntas, generar una SEED determinista y jugar desde un móvil.

## Archivos
- index.html: generador de preguntas y SEED
- player.html: pantalla para introducir la SEED y responder
- generator.js: lógica del generador
- player.js: lógica del jugador

## Cómo usarlo
1. Abre index.html en el navegador.
2. Añade preguntas, responde correctamente y genera la SEED.
3. Copia, descarga o carga la SEED.
4. Abre player.html o entra en la pantalla del jugador para probar la SEED.

## Alojamiento gratuito
La app es estática, así que puedes publicarla en:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

### Opción recomendada: GitHub Pages
1. Sube estos archivos a un repositorio de GitHub.
2. En Settings > Pages, selecciona Deploy from a branch.
3. Elige la rama principal y la carpeta raíz.
4. Guarda y espera a que se publique.

## Notas
- Las respuestas se comparan sin distinguir mayúsculas/minúsculas y sin tildes.
- La SEED se genera de forma determinista usando LZ-String y JSON.
- El diseño está preparado para pantallas pequeñas.
