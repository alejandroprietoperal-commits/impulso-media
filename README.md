# impulso-media · rama `app`

Lo que sirve jsDelivr a Impulso: por cada ejercicio, su animación (`.webp`) y
su miniatura fija (`.jpg`). Solo esto, para no pasar de los 50 MB que admite
jsDelivr. Los GIF originales están en la rama `main`.

Se genera con `node scripts/gym-import.js` en el repositorio de Impulso. La app
apunta a un commit concreto de esta rama (`src/lib/assetUrl.ts`): no reescribir
su historia, que hay móviles pidiendo commits anteriores.
