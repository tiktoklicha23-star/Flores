# Un presente para vos

Página estática, adaptable a celular y computadora, sin dependencias. Abrí index.html para verla. La intro conduce a una sorpresa de flores, hojas y brillos animados.

## Canción de YouTube

La canción elegida es https://www.youtube.com/watch?v=SVH0HOjesP0. El reproductor se muestra al abrir la sorpresa e intenta reproducir con sonido. Si el navegador bloquea el inicio, tocá reproducir en el video. Requiere internet. YouTube puede impedir la reproducción en otros sitios o al abrir el archivo local: probá la página publicada en GitHub Pages. El botón Escuchar en YouTube permite abrir el video original. No se incluye la lista de radio del enlace.

## Elegir música

El botón Elegir canción permite probar un audio desde tu dispositivo. Ese archivo solo se reproduce en esa sesión; no se envía ni se comparte con otros visitantes.

Para que todos escuchen la misma canción, copiá un archivo llamado cancion.mp3 junto a index.html. En index.html cambiá `const CANCION = '';` por `const CANCION = 'cancion.mp3';`. La canción comienza al tocar Mirar sorpresa. Utilizá un audio que puedas publicar.

## GitHub Pages

1. Creá un repositorio llamado sorpresa en tu cuenta de GitHub.
2. Subí el contenido de esta carpeta a la raíz del repositorio, incluida la carpeta .github, en la rama main. También podés subir solo index.html y la canción y usar la opción Deploy from a branch (main / root).
3. Para usar el workflow incluido: en Settings → Pages → Build and deployment elegí GitHub Actions.
4. En Actions ejecutá Publicar sorpresa con Run workflow, o realizá un nuevo commit a main.
5. El enlace público aparece en Settings → Pages y tendrá el formato https://TU-USUARIO.github.io/sorpresa/.

Si usás git desde tu PC, los archivos de esta carpeta ya están listos para el primer commit. No hace falta instalar Node ni ejecutar una compilación.

## Personalizar

Los mensajes están en index.html. Cambiá los textos de h1, p y h2. El estilo respeta la preferencia de movimiento reducido del dispositivo.
