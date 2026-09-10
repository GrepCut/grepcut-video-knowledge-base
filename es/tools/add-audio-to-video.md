# Agregar audio a video en línea

Arrastra un video y un archivo de audio: GrepCut reemplaza la banda sonora sin recodificar la imagen. Nada sale de tu dispositivo.

HTML: https://grepcut.com/es/tools/add-audio-to-video

## Cómo agregar audio a un video en tu navegador

1. **Elige tu video**: Arrastra un archivo MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP o MPEG a GrepCut. Tu video permanece en tu dispositivo.
2. **Elige tu audio**: Agrega un archivo MP3, WAV, AAC, M4A, FLAC, OGG u Opus. Este archivo se convertirá en la nueva banda sonora.
3. **Mezcla y exporta**: Haz clic en Mezclar y exportar. GrepCut multiplexa el flujo de video y tu nuevo audio en un solo MP4.
4. **Descarga el resultado**: Guarda el MP4 con -with-audio añadido al nombre del archivo. La exportación termina en el más corto de tus dos archivos de entrada.

¿Necesitas superponer música de fondo con la voz original, ajustar volumen, fundir audio o sincronizar una pista por unos fotogramas? Abre [GrepCut Studio](/) en su lugar.

## Qué cambia realmente este intercambio de audio

Si ya tienes un video terminado y un archivo de voz en off, canción, narración o audio limpio por separado, no necesitas un editor completo solo para reemplazar la banda sonora. GrepCut toma el flujo de video de tu primer archivo y el flujo de audio de tu segundo archivo, y los escribe en un solo MP4.

Tu banda sonora original no se conserva. El nuevo archivo de audio se convierte en la única pista de audio en la exportación. Esto es útil cuando tu clip está en silencio, tiene ruido, está silenciado por una plataforma o se exportó con la pista de audio incorrecta.

El flujo de video se copia cuando es posible, por lo que la imagen no se vuelve a comprimir solo porque cambiaste el audio. Si el códec de video no se puede copiar limpiamente en MP4, es posible que necesites un flujo de trabajo diferente en el editor completo.

La idea clave es simple: estás reemplazando una pista, no reconstruyendo toda la edición.

## Reemplazo de audio vs. edición completa

| Lo que necesitas | Usa esta herramienta rápida | Usa GrepCut Studio |
| --- | --- | --- |
| Reemplazar el audio deficiente de la cámara con un MP3 o WAV separado | Sí, este es el flujo de trabajo principal | Solo si también necesitas ediciones |
| Agregar voz en off a una grabación de pantalla silenciosa | Sí, si un archivo de audio es suficiente | Úsalo para ajustes de sincronización |
| Conservar el audio original y agregar música encima | No, el audio original se reemplaza | Sí, usa múltiples pistas |
| Fundir música de entrada o salida | No, solo reemplazo rápido | Sí, usa controles de volumen |
| Corregir audio que comienza tarde o temprano | No hay controles de sincronización precisos aquí | Sí, alinéalo en la línea de tiempo |

Usa la herramienta rápida cuando tu video y el audio de reemplazo ya coincidan bien. Usa el Studio cuando tu audio necesite edición, mezcla o ajuste de sincronización.

## Formatos de video y audio compatibles

Comienza con un archivo de video. GrepCut está diseñado para entradas MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP y MPEG, además de otros archivos de video legibles cuando el navegador y FFmpeg pueden analizarlos.

Luego agrega un archivo de audio. MP3, WAV, AAC, M4A, FLAC, OGG y Opus son las entradas de audio probadas. La salida siempre es un MP4, lo que facilita compartir, reproducir e importar el resultado en aplicaciones comunes.

### Algunas notas prácticas sobre formatos:

- **MP4 y MOV**: buenos para clips de teléfono, grabaciones de pantalla, exportaciones de cámara y borradores de redes sociales.
- **WebM y MKV**: útiles cuando tu fuente proviene de un grabador de navegador, descarga o flujo de trabajo de código abierto.
- **WAV y FLAC**: buenos para voz en off limpia o masters de música antes de crear el MP4 final.
- **OGG y Opus**: útiles para audio grabado por aplicaciones web, juegos o herramientas multimedia abiertas.

Si un archivo se abre pero la exportación falla, el culpable habitual no es la extensión del archivo, sino el códec dentro del contenedor.

## Por qué tu exportación termina en el archivo más corto

GrepCut recorta la exportación al archivo de entrada más corto para que no obtengas una cola negra larga, un final silencioso o audio adicional oculto después de que termine la imagen. Si tu canción es más larga que el clip, la canción se corta al final del video. Si tu voz en off es más corta que el clip, el video exportado termina cuando termina la voz en off.

Ese comportamiento es intencional para una herramienta de reemplazo rápido. Mantiene el resultado predecible sin agregar bucle, relleno, fundidos o generación de silencio. Para esas opciones de sincronización, usa la línea de tiempo completa en GrepCut Studio.

## Lo que obtienes con un intercambio de audio basado en navegador

### Advantages

- Tu video y audio permanecen en tu dispositivo sin subida.
- La imagen no se vuelve a codificar cuando es posible la copia de flujo.
- Obtienes un MP4 que es más fácil de reproducir y compartir.
- Puedes reemplazar audio ruidoso, silenciado o incorrecto sin abrir una línea de tiempo completa.
- Puedes usar entradas de video comunes y formatos de audio comunes.

### Disadvantages

- Solo se usa un archivo de audio de reemplazo.
- El audio original se elimina en lugar de mezclarse debajo.
- Los cambios de volumen, fundidos, duplicación y sincronización exacta necesitan GrepCut Studio.
- Los archivos muy grandes dependen de la memoria de tu dispositivo y los límites del navegador.
- Algunos códecs inusuales pueden necesitar conversión antes de que encajen dentro de MP4.

> renderizar hace que el video sea 3 veces más grande o hay una pérdida significativa de calidad para el mismo tamaño de archivo
>
> Reddit r/davinciresolve

## Preguntas frecuentes sobre agregar audio a video

### ¿Se puede reemplazar el audio en un MP4 sin volver a renderizar el video?

Sí, cuando el flujo de video se puede copiar en el MP4 de salida. GrepCut intenta copiar el flujo de imagen en lugar de volver a codificarlo, por lo que cambiar la banda sonora no implica automáticamente perder calidad de imagen.

### ¿Se subirá tu video o audio?

No. GrepCut realiza el intercambio de audio localmente en tu navegador usando FFmpeg compilado a WebAssembly. Tus archivos permanecen en tu dispositivo.

### ¿Se puede conservar el sonido original y agregar música encima?

No en esta herramienta rápida. El audio de reemplazo se convierte en la única banda sonora. Usa [GrepCut Studio](/) si necesitas música, diálogos y efectos de sonido reproduciéndose juntos.

### ¿Qué sucede si tu audio es más largo que tu video?

La exportación termina al final del archivo más corto. Si tu audio dura más que el video, se recorta. Si tu audio es más corto, el video termina con él.

### ¿Se puede sincronizar audio que comienza demasiado temprano o demasiado tarde?

Esta herramienta no incluye controles de desplazamiento. Si tu voz en off necesita alineación a nivel de fotograma, abre el video en [GrepCut Studio](/) y mueve el audio en la línea de tiempo.

### ¿A qué formatos se puede agregar audio?

Puedes comenzar con video MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP o MPEG. Tu audio de reemplazo puede ser MP3, WAV, AAC, M4A, FLAC, OGG u Opus. El archivo descargado es MP4.

### ¿Por qué GrepCut exporta MP4 en lugar de mantener el contenedor original?

MP4 es ampliamente compatible con navegadores, teléfonos, editores y aplicaciones sociales. Mantener un contenedor de salida también hace que la herramienta rápida sea más simple y predecible.

### ¿Perderá calidad tu archivo?

La imagen debería permanecer igual cuando la copia de flujo funciona. El audio se toma de tu archivo de reemplazo y se multiplexa en la salida, por lo que el resultado depende de la calidad del archivo de audio que proporciones.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre reemplazar audio en MP4 sin renderizar](https://www.reddit.com/r/davinciresolve/comments/1fnsfjb/how_do_i_replace_the_audio_of_an_mp4_without/)
- [Hilo de Super User sobre reemplazar audio en video con FFmpeg](https://superuser.com/questions/1137612/ffmpeg-replace-audio-in-video)
- [Hilo de Super User sobre comportamiento de duración de audio y video](https://superuser.com/questions/801547/ffmpeg-add-audio-but-keep-video-length-the-same-not-shortest)
- [Discusión en Reddit sobre editar audio sin volver a codificar video](https://www.reddit.com/r/VideoEditing/comments/v1n6tu/edit_audio_without_reencoding_video/)
- [Documentación de FFmpeg sobre especificadores de flujo y copia de códec](https://ffmpeg.org/ffmpeg.html)
- [Guía de MDN sobre formatos de contenedor multimedia](https://developer.mozilla.org/es/docs/Web/Media/Guides/Formats/Containers)

## Reemplaza la banda sonora de tu video de forma privada

Abre GrepCut, agrega tu video, agrega tu audio de reemplazo y exporta un MP4 sin subir tus archivos.

## Herramientas relacionadas

- [Silenciar video](https://grepcut.com/es/tools/mute-video) - elimina la banda sonora antes de añadir una nueva.
- [Recortador de video](https://grepcut.com/es/tools/video-trimmer) - recorta el clip antes de reemplazar el audio.
- [Incrustar subtítulos SRT](https://grepcut.com/es/tools/burn-srt-subtitles-to-video) - incrusta los subtítulos después de reemplazar la banda sonora.
