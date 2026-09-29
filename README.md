# impulso-media

Imágenes de los ejercicios de gimnasio de Impulso. Están aquí, y no en la web,
porque Vercel guarda entera cada versión publicada y estas imágenes (17 MB) se
copiaban en todas.

La app las pide a jsDelivr con una etiqueta fija:

    https://cdn.jsdelivr.net/gh/alejandroprietoperal-commits/impulso-media@v1/gym/<archivo>

Lo de una etiqueta no cambia nunca. Para cambiar imágenes: subirlas, crear una
etiqueta nueva (v2…) y cambiarla en Impulso (`src/lib/assetUrl.ts` y
`vercel.json`). Después, `node scripts/media-check.js` en Impulso comprueba que
está todo publicado.

No borrar ni reescribir etiquetas ya publicadas: hay móviles que las piden.
