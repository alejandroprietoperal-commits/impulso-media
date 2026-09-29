# impulso-media

Imágenes de los ejercicios de gimnasio de Impulso. Están aquí, y no en la web,
porque Vercel guarda entera cada versión publicada y estas imágenes (17 MB) se
copiaban en todas.

La app las pide a jsDelivr fijadas a un commit concreto de este repositorio:

    https://cdn.jsdelivr.net/gh/alejandroprietoperal-commits/impulso-media@<commit>/gym/<archivo>

Lo de un commit no cambia nunca. Para cambiar imágenes: subirlas aquí y poner el
commit nuevo en Impulso (`src/lib/assetUrl.ts` y `vercel.json`). Después,
`node scripts/media-check.js` en Impulso comprueba que está todo publicado.

No reescribir la historia de este repositorio (nada de force-push): hay móviles
que piden las imágenes de commits anteriores.
