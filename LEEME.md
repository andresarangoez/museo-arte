# ¿Qué destruimos cuando destruimos el arte? — Museo interactivo

## Publicar en GitHub Pages
1. Crea un repositorio público (por ejemplo `museo-arte`) y sube **todo el contenido de esta carpeta** (index.html, img/, js/, audio/).
2. En el repositorio: **Settings → Pages → Branch: main / (root) → Save**.
3. En 1 o 2 minutos tendrás la dirección `https://TU-USUARIO.github.io/museo-arte/`.

## Controlar con el celular
1. Abre la presentación en el computador (desde GitHub Pages) y pulsa **R** o el ícono del celular.
2. Escanea el código QR con el celular. En el teléfono verás los botones, tus notas (verbal, vocal, visual) y el cronómetro.
3. Los dos dispositivos necesitan internet, pero pueden estar en redes distintas (por ejemplo, el computador en el wifi y el celular con datos). La conexión pasa por un servidor público (MQTT), así que funciona aunque la red bloquee conexiones directas. Si no hay internet, usa el teclado o un presentador inalámbrico (clicker).

## Imágenes
Los espacios ya tienen fotos de Wikimedia Commons (Partenón, Altamira, Keops, Goya y Palmira). Se cargan directo desde Commons cuando la página está en GitHub Pages o se abre con internet. Para ver los créditos y licencias, pulsa la tecla **C** durante la presentación.

Para cambiar una imagen, o para que funcione sin internet, sube tu archivo a `img/obras/` con el nombre del espacio. Ese archivo tiene prioridad sobre la foto de Commons:
`monumento`, `rupestre`, `monumento-historico`, `pintura-historica`, `protesta`, `palmira-antes`, `palmira-despues` (.jpg, .png o .webp).
También puedes arrastrar una imagen sobre cualquier espacio durante la presentación.

## Música
- Por defecto suena una atmósfera ambiental generada en vivo, tranquila y sin tono motivacional.
- Para usar tu propia canción, súbela como `audio/musica.mp3` y sonará sola. También puedes cargarla desde el botón ♪.

## Teclas
→ / Espacio: avanzar · ← retroceder · N: notas y cronómetro · M: música · F: pantalla completa · R: celular · B: pantalla negra · C: créditos · H: ejercicio de respiración · 1–9, 0: ir a una sala. La presentación abre directo en la Sala I; la música y el cronómetro empiezan con la primera tecla o clic en el computador.
