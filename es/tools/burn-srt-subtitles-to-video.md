# Quemar subtítulos SRT en video en línea

Arrastra tu video y un archivo SRT: GrepCut quema los subtítulos SRT en cada fotograma. Ideal para accesibilidad, compartir en redes sociales y plataformas de reproducción silenciosa.

HTML: https://grepcut.com/es/tools/burn-srt-subtitles-to-video

## Cómo incrustar subtítulos SRT en tu video

1. **Añade tu video**: Arrastra un archivo MP4, MOV, WebM o MKV. Tu video permanece en tu dispositivo.
2. **Añade tu archivo SRT**: Arrastra o busca tu archivo de subtítulos .srt. GrepCut analiza las marcas de tiempo y el texto de los subtítulos localmente en tu navegador.
3. **Vista previa de los subtítulos**: Ajusta la posición, tamaño, fuente y ajuste de línea antes de exportar, para evitar rostros tapados, texto recortado o saltos de línea incómodos.
4. **Incrusta y exporta a MP4**: Haz clic en 'Incrustar subtítulos SRT' para grabar los subtítulos en los fotogramas del video y guardar un nuevo MP4.

¿Aún no tienes un archivo SRT? Abre [GrepCut Studio](/) para generar subtítulos a partir del habla, editar la transcripción y exportar SRT.

## Cuándo tiene sentido incrustar subtítulos SRT

Los subtítulos SRT incrustados pasan a formar parte de la imagen. Si tu video se comparte en un feed, se reproduce en una aplicación con los subtítulos desactivados o lo descarga alguien que quizás no conserve el archivo SRT adjunto, el texto sigue apareciendo.

Esto es útil cuando necesitas una visualización predecible en clips para redes sociales, demostraciones cortas, videos de formación interna o exportaciones traducidas. No dependes de que el reproductor detecte una pista de subtítulos separada ni de que la plataforma mantenga tu archivo de subtítulos adjunto.

La compensación es simple: una vez que incrustas los subtítulos SRT en el video, no puedes desactivarlos ni editar un error tipográfico dentro del MP4 exportado. Primero corrige el SRT, previsualízalo y luego incrusta la versión final.

### Usa esta herramienta cuando necesites subtítulos que siempre se muestren:

- **Clips para redes sociales**: haz que tu diálogo sea legible cuando el video comienza silenciado en un feed.
- **Archivos para revisión del cliente**: envía un solo MP4 sin pedirle al espectador que cargue un archivo .srt aparte.
- **Versiones traducidas**: fija un idioma en la exportación cuando entregas una versión definitiva.
- **Compatibilidad con reproductores**: evita casos en los que una aplicación de video ignora un archivo de subtítulos externo o lo muestra con un estilo incorrecto.

Si también necesitas subtítulos conmutables para accesibilidad o varios idiomas, conserva también tu archivo SRT original. Los subtítulos incrustados son visualmente fiables, pero no sustituyen a una pista de subtítulos ocultos adecuada cuando la plataforma la admite.

## Subtítulos SRT incrustados vs. pista de subtítulos blandos

| Necesidad | Subtítulos SRT incrustados | Subtítulos blandos |
| --- | --- | --- |
| Siempre visibles | Sí. El texto forma parte de cada fotograma exportado. | No. El reproductor o espectador puede desactivar los subtítulos. |
| Editar después de exportar | No. Debes corregir el SRT y exportar de nuevo. | Sí. Puedes reemplazar o editar el archivo de subtítulos. |
| Varios idiomas | Ideal para un idioma fijo por exportación. | Mejor cuando el espectador debe elegir un idioma. |
| Compatibilidad con plataformas | Funciona en cualquier lugar donde se reproduzca el MP4 exportado. | Depende de si la aplicación admite tu archivo de subtítulos. |
| Controles de accesibilidad | Limitados. El espectador no puede redimensionar, mover o cambiar el estilo de los subtítulos. | Mejor. Los reproductores compatibles pueden exponer la configuración de subtítulos. |

Si tu objetivo es un MP4 listo para redes sociales con subtítulos que no puedan desaparecer, incrusta el SRT. Si tu objetivo son subtítulos seleccionables, sube la pista SRT o VTT por separado donde la plataforma lo admita.

## Qué hace GrepCut con tu archivo SRT

Un archivo SRT es texto plano con señales numeradas, marcas de tiempo de inicio y fin, y las líneas de subtítulos que deben aparecer durante cada intervalo de tiempo. GrepCut lee esas señales localmente y dibuja el texto correspondiente sobre tu video durante la exportación.

La herramienta admite subtítulos SRT estándar SubRip con texto plano. Las etiquetas HTML dentro del SRT, como `<i>`, se eliminan automáticamente para que la incrustación sea predecible.

No se admite el estilo de subtítulos ASS y SSA. Si tus subtítulos de origen dependen de colores por señal, efectos de karaoke, contornos o posicionamiento complejo, conviértelos o simplifícalos a SRT plano antes de usar esta herramienta.

### Antes de exportar, verifica estos detalles:

- **Sincronización**: reproduce algunos momentos donde el diálogo comienza y termina para confirmar que el SRT está sincronizado.
- **Longitud de línea**: usa la vista previa de ajuste para que los subtítulos largos no se salgan del video.
- **Posición**: aleja los subtítulos de rostros, interfaz de producto, tercios inferiores o botones de la plataforma.
- **Redacción final**: corrige errores tipográficos antes de incrustar, porque el MP4 exportado no se puede editar como un archivo de texto.

## Ventajas y limitaciones de incrustar SRT en tu navegador

### Advantages

- Tu video y archivo SRT permanecen en tu dispositivo.
- Obtienes una vista previa en vivo antes de exportar.
- El MP4 exportado tiene subtítulos integrados en los fotogramas del video.
- Puedes elegir posición, tamaño, fuente y ajuste de línea.
- No hay subida ni marca de agua.

### Disadvantages

- Los subtítulos incrustados no se pueden desactivar después de la exportación.
- Un error tipográfico requiere corregir el SRT y exportar de nuevo.
- No se admiten colores por señal, estilo ASS ni efectos SSA.
- La renderización lleva más tiempo que recortar o silenciar porque cada fotograma debe decodificarse, componerse y recodificarse.
- Necesitas un navegador compatible con WebCodecs como Chrome, Edge u Opera.

> Si tienes un archivo con subtítulos incrustados, no se pueden ocultar.
>
> Discusión de Super User sobre subtítulos incrustados

## Incrustar subtítulos SRT en video - Preguntas frecuentes

### ¿Se puede incrustar un archivo SRT en un MP4 en línea?

Sí. Arrastra tu video y tu archivo .srt a GrepCut, previsualiza los subtítulos y luego exporta un nuevo MP4 con los subtítulos SRT grabados en los fotogramas.

### ¿Se subirá mi video o archivo SRT?

No. Tu video y archivo de subtítulos se leen en tu navegador. No se envía nada a un servidor, lo cual es útil cuando tu clip contiene reuniones privadas, borradores, trabajo de clientes o contenido inédito.

### ¿Puedo personalizar el aspecto de los subtítulos SRT?

Sí. Puedes previsualizar y ajustar la posición, tamaño, fuente y ajuste de línea antes de exportar. No se admiten colores por línea, efectos ASS/SSA ni estilos avanzados de subtítulos.

### ¿Por qué incrustar subtítulos lleva más tiempo que añadir un archivo de subtítulos?

Incrustar subtítulos SRT modifica el video en sí. Tu navegador debe decodificar el video, dibujar el texto de los subtítulos en los fotogramas correctos y codificar un nuevo MP4.

### ¿Puedo eliminar los subtítulos incrustados después?

No de forma limpia. Los subtítulos incrustados son parte de la imagen exportada, por lo que debes conservar tu video original y el archivo SRT por si necesitas editar o exportar de nuevo.

### ¿Qué pasa si mis subtítulos están desincronizados?

La sincronización proviene de tu archivo SRT. Si los subtítulos aparecen demasiado pronto o demasiado tarde en la vista previa, corrige las marcas de tiempo en el SRT o regenera los subtítulos en [GrepCut Studio](/) antes de incrustar.

### ¿Necesito primero un archivo SRT?

Sí. Esta herramienta incrusta un archivo .srt existente en tu video. Si solo tienes un video, ábrelo en [GrepCut Studio](/) para transcribir el habla, editar la transcripción y exportar SRT.

### ¿Qué navegadores funcionan mejor para incrustar subtítulos SRT?

Usa un navegador compatible con WebCodecs como Chrome, Edge u Opera. Si tu navegador actual no puede exportar, abre los mismos archivos en un navegador Chromium compatible.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre subtítulos incrustados, video social y compensaciones de accesibilidad](https://www.reddit.com/r/deaf/comments/1n6unqv/question_about_accessibility_for_video_platforms/)
- [Discusión en Reddit sobre subtítulos para videos sociales](https://www.reddit.com/r/socialmedia/comments/1afv64z/does_it_matter_how_i_do_subtitles_for_social/)
- [Hilo de Super User explicando los subtítulos incrustados como texto de video no ocultable](https://superuser.com/questions/1229037/hardcoded-subtitles-in-m4v-file-dont-show-up-in-youtube)
- [Hilo de Super User sobre incrustación de subtítulos SRT con procesamiento de video](https://superuser.com/questions/869248/hardcoding-subs-with-ffmpeg)
- [Descripción general de la API WebCodecs de MDN](https://developer.mozilla.org/es/docs/Web/API/WebCodecs_API)
- [Ayuda de YouTube sobre archivos de subtítulos y subtítulos ocultos compatibles](https://support.google.com/youtube/answer/2734698)

## ¿Necesitas generar primero el archivo SRT?

Abre GrepCut Studio para transcribir tu video con IA, editar la transcripción, exportar SRT o incrustar subtítulos directamente en tu clip final.

## Herramientas relacionadas

- [Añadir audio al video](https://grepcut.com/es/tools/add-audio-to-video) - reemplaza la banda sonora antes de grabar los subtítulos.
- [Silenciar video](https://grepcut.com/es/tools/mute-video) - elimina el audio cuando los subtítulos contienen el diálogo.
- [Recortador de video](https://grepcut.com/es/tools/video-trimmer) - recorta el clip antes de incrustar los subtítulos.
