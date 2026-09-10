# Recortador de video gratuito en línea

Recorta un video hasta la parte que necesitas en menos de 2 segundos. Usando copia de flujo sin pérdidas alineada con fotogramas clave, todo ocurre localmente en tu navegador sin subida ni pérdida de calidad.

HTML: https://grepcut.com/es/tools/video-trimmer

## Cómo Recortar un Video en tu Navegador

1. **Añade tu video**: Arrastra tu archivo al recortador o haz clic para buscar. Tu video se carga localmente en la vista previa.
2. **Elige la parte que deseas**: Arrastra los controles de inicio y fin, luego previsualiza el rango antes de exportar.
3. **Exporta tu corte**: Crea un MP4 recortado usando copia de flujo alineada con fotogramas clave, o continúa editando en GrepCut Studio.

¿Necesitas varios cortes, subtítulos, música o eliminar una sección intermedia? Abre el clip en [GrepCut Studio](/).

## Por Qué Tus Exportaciones de Video Son Tan Rápidas

Cuando solo necesitas cortar el inicio o el final de un clip, subir todo el archivo a un servidor puede parecer innecesario. GrepCut mantiene tu archivo en tu dispositivo y lo recorta directamente en tu navegador.

El recortador usa WebCodecs y MediaBunny para leer el archivo multimedia, copiar los paquetes de video y audio ya codificados, y reempaquetarlos en un nuevo MP4. Como tu navegador no necesita decodificar y recodificar cada fotograma, la exportación suele terminar en segundos.

### Obtienes un corte rápido porque GrepCut evita la parte más lenta de la edición:

- **Sin transcodificación completa**: El rango seleccionado se copia del flujo fuente en lugar de codificarse desde cero.
- **Sin espera de carga**: Tu archivo permanece en tu dispositivo, así que no tienes que esperar a que se cargue en un servidor antes de recortarlo.
- **Sin pérdida de calidad generacional**: La ruta de copia de flujo preserva el material codificado original en el rango exportado.

## Qué Significa para Ti el Corte Alineado con Fotogramas Clave

Un video comprimido no es solo una pila de imágenes completas. La mayoría de los fotogramas dependen de fotogramas cercanos, y los fotogramas clave son los puntos seguros donde la reproducción puede comenzar limpiamente.

Por eso, un recortador de copia de flujo sin pérdidas puede ajustar tu corte al fotograma clave utilizable más cercano en lugar de cortar en cualquier fotograma arbitrario. Obtienes un MP4 rápido y compatible con estándares, pero el inicio o final exportado puede ser ligeramente anterior o posterior a la posición del control.

Si necesitas un recorte exacto por fotograma, efectos visuales, transiciones o un corte en medio de un clip, usa el editor completo en lugar del recortador de un solo rango.

## Recortador de Navegador vs Recortador en Línea Tradicional

| Lo que necesitas | Recortador de Video GrepCut | Recortador de servidor típico |
| --- | --- | --- |
| Privacidad | Tu video permanece en tu dispositivo | Tu video se sube antes del procesamiento |
| Velocidad | Copia de flujo rápida para un rango continuo | Tiempo de subida más procesamiento en servidor |
| Calidad | Preserva la calidad original para el rango copiado | Puede recodificar y añadir pérdida generacional |
| Precisión de corte | Alineado con fotogramas clave seguros | Puede ser exacto por fotograma si el servidor recodifica |
| Mejor uso | Eliminar rápidamente el inicio o final de un clip | Ediciones más pesadas, cambios de formato o exportaciones exactas por fotograma |

Elige GrepCut cuando quieras un corte privado, rápido y sin subida. Elige un editor completo cuando tu edición requiera temporización exacta por fotograma o múltiples rangos separados.

## Antes de Recortar

### Advantages

- Tu archivo no se sube a un servidor.
- La vista previa se actualiza mientras ajustas el rango.
- La copia de flujo mantiene el rango seleccionado con calidad original.
- Sin marca de agua, sin cuenta y sin instalación.

### Disadvantages

- Los puntos de corte se alinean con fotogramas clave cercanos.
- Archivos muy grandes dependen de la memoria de tu dispositivo.
- Esta herramienta mantiene solo un rango continuo.
- Necesitas un navegador con soporte para WebCodecs.

> solo puedes cortar un video en un fotograma clave (sin codificar)
>
> Discusión de Reddit r/ffmpeg

## Preguntas Frecuentes sobre el Recortador de Video

### ¿Se sube tu video cuando lo recortas?

No. Tu archivo se procesa localmente en tu navegador, por lo que no sale de tu dispositivo.

### ¿Recortar reducirá la calidad de tu video?

No se introduce pérdida de calidad en la ruta de copia de flujo. GrepCut copia el material codificado de tu rango seleccionado y lo reempaqueta en un nuevo MP4.

### ¿Por qué tu corte no es exacto por fotograma?

El recorte de video sin pérdidas debe respetar los fotogramas clave. Si tu tiempo de inicio o fin elegido cae entre fotogramas clave, GrepCut alinea el corte a un punto seguro cercano para que el MP4 exportado se reproduzca correctamente.

### ¿Puedes eliminar la parte central de un video?

Este recortador mantiene un solo rango continuo. Si necesitas eliminar una sección intermedia o hacer varios cortes, abre el clip en [GrepCut Studio](/).

### ¿Puedes recortar un archivo de video grande?

Sí, pero la memoria de tu navegador y dispositivo sigue siendo importante. Como el archivo se maneja localmente, los videos muy grandes pueden estar limitados por tu computadora en lugar de por un límite de subida.

### ¿Qué navegadores funcionan mejor?

Usa un navegador con soporte para WebCodecs, como Chrome, Edge u Opera. Si tu navegador no admite las API multimedia necesarias, es posible que el recortador no funcione.

### ¿Qué archivo obtienes después de recortar?

Exportas un MP4 que contiene el rango continuo seleccionado. El objetivo es un archivo ampliamente reproducible sin subir ni transcodificar todo tu video.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre cortar video sin recodificar en fotogramas clave](https://www.reddit.com/r/ffmpeg/comments/10tj7nu/can_you_only_cut_videos_without_reencoding_on/)
- [Discusión en Reddit sobre recortar video sin recodificar](https://www.reddit.com/r/ffmpeg/comments/1qag2ug/trimming_video_without_reencoding/)
- [Discusión en Super User sobre cortar video con mínima o ninguna recodificación](https://superuser.com/questions/1850814/how-to-cut-a-video-with-ffmpeg-with-no-or-minimal-re-encoding)
- [Discusión en Super User sobre corte rápido de video y copia de flujo](https://superuser.com/questions/1643484/fast-and-relatively-accurate-cutting-from-a-video)
- [Resumen de la API WebCodecs de MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [Kit de herramientas multimedia MediaBunny para navegador](https://mediabunny.dev/)

## Recorta tu Clip y Luego Sigue Editando

Usa el recortador para un corte privado y rápido. Cuando tu clip necesite subtítulos, música, cambios de diseño o una línea de tiempo completa, ábrelo en GrepCut Studio y sigue creando en el navegador.

## Herramientas Relacionadas

- [Recortar Video](https://grepcut.com/es/tools/crop-video) - reencuadra tu clip a una región o relación de aspecto.
- [Redimensionar Video](https://grepcut.com/es/tools/resize-video) - escala clips recortados a una nueva resolución o relación de aspecto.
- [Silenciar Video](https://grepcut.com/es/tools/mute-video) - elimina la pista de audio de tu clip.
