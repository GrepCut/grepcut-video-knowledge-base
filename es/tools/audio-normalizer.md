# Normalizador de Volumen de Audio Online

Mide la sonoridad integrada y normaliza tus pistas a -14, -16 o -23 LUFS. Funciona completamente en tu navegador sin necesidad de subir archivos ni crear una cuenta.

HTML: https://grepcut.com/es/tools/audio-normalizer

## Cómo Normalizar el Volumen de Audio Online

1. **Sube tu audio**: Arrastra un archivo MP3, WAV, M4A u OGG a la tarjeta de carga.
2. **Elige tu objetivo LUFS**: Selecciona Streaming a -14 LUFS, Podcast a -16 LUFS o Broadcast a -23 LUFS.
3. **Normaliza y exporta WAV**: Haz clic en Normalizar para medir el volumen, aplicar ganancia segura con limitación de pico y descargar una copia en WAV.

Tu archivo se procesa localmente en tu navegador. No se sube nada a GrepCut.

## Por Qué Tu Audio Necesita LUFS, No Solo Normalización de Pico

Si tu clip alcanza picos cercanos a 0 dB pero suena bajo en comparación con otro audio, la normalización de pico no resolverá el problema real. Los picos solo muestran la muestra más alta, mientras que LUFS estima qué tan fuerte se siente tu pista con el tiempo.

GrepCut mide el volumen integrado con ponderación K, luego aplica ganancia hacia tu objetivo seleccionado respetando un límite de pico de -1 dBTP. Esto ayuda a que tu audio se acerque más a un objetivo de volumen para streaming, podcast o transmisión sin empujar los picos al recorte.

### Úsalo cuando quieras un volumen percibido consistente antes de compartir, publicar o editar más.

Si tu archivo ya es muy fuerte y no tiene margen dinámico, el límite de pico puede impedir que la herramienta alcance el objetivo LUFS exacto. En ese caso, un resultado más seguro suele ser mejor que uno recortado.

## ¿Qué Objetivo LUFS Deberías Elegir?

| Objetivo | Ideal para | Qué hace |
| --- | --- | --- |
| -14 LUFS | Avances de video en streaming o música | Un objetivo de volumen común cuando quieres que el audio se sitúe cerca de los niveles de reproducción de las principales plataformas de streaming. |
| -16 LUFS | Podcasts y clips de voz | Un objetivo práctico para contenido centrado en la voz, donde la claridad y la consistencia importan más que el volumen máximo. |
| -23 LUFS | Entrega tipo broadcast | Un objetivo más silencioso alineado con flujos de trabajo de volumen de transmisión estilo EBU R128. |

Estos ajustes predefinidos son puntos de partida. Tu plataforma de entrega final puede aplicar su propia normalización de reproducción después de que publiques.

## Qué Sucede Dentro de Tu Navegador

Cuando agregas un archivo, tu navegador decodifica el audio para que GrepCut pueda analizar la forma de onda. La herramienta mide el volumen en toda la pista, calcula la ganancia necesaria para tu objetivo LUFS seleccionado y limita el resultado para que los picos se mantengan por debajo del límite.

Debido a que el procesamiento es local, tu audio permanece en tu dispositivo. Los archivos muy largos pueden tardar más porque tu navegador tiene que decodificar y procesar el audio en memoria.

- **Privado por diseño**: Tu audio fuente no se sube a un servidor.
- **Consciente de LUFS**: La herramienta apunta al volumen percibido, no solo al pico de muestra más alto.
- **Exportación WAV**: El resultado normalizado se descarga como archivo WAV para editar, archivar o convertir.

## Cuándo Ayuda Más la Normalización de Volumen

Usa la normalización LUFS cuando tu nota de voz, segmento de podcast, grabación de pantalla o clip musical suene mucho más bajo o más alto que el resto de tu proyecto. Es especialmente útil antes de ensamblar varios clips en una misma línea de tiempo.

Para voz, es posible que aún quieras limpiar ruido, ecualizar, comprimir o editar pausas antes de la normalización. La normalización de volumen suele ser el paso final de ajuste de nivel, no un sustituto para arreglar una grabación ruidosa o una interpretación desigual.

## Ventajas y Límites del Normalizador de Audio

### Advantages

- Puedes normalizar MP3, WAV, M4A u OGG sin subir tu archivo.
- Puedes elegir ajustes predefinidos LUFS claros para flujos de trabajo de streaming, podcast o broadcast.
- La limitación de pico reduce el riesgo de recorte cuando se agrega ganancia.

### Disadvantages

- El formato de exportación es WAV, no MP3 o M4A.
- Un archivo sin margen dinámico puede no alcanzar el objetivo LUFS exacto sin recortar.
- La compatibilidad de decodificación del navegador puede variar según el códec del archivo y el dispositivo.

> La normalización ajusta cada canción al mismo nivel de pico, pero eso no es lo mismo que ajustarlas al mismo nivel de volumen.
>
> Reddit r/audioengineering

## Preguntas Frecuentes sobre el Normalizador de Audio

### ¿Se puede normalizar audio a -14 LUFS online?

Sí. Elige el ajuste predefinido Streaming para apuntar a -14 LUFS, luego exporta el resultado normalizado como WAV. Tu navegador realiza el procesamiento localmente, por lo que tu archivo no se sube.

### ¿Debería usar -14 LUFS o -16 LUFS?

Usa -14 LUFS cuando quieras un objetivo común de estilo streaming. Usa -16 LUFS cuando prepares audio de voz, como un segmento de podcast. Si no estás seguro, elige el ajuste que coincida con dónde se usará tu audio.

### ¿Se puede normalizar audio para volumen de transmisión?

Sí. Elige el ajuste predefinido Broadcast para apuntar a -23 LUFS. Esto es útil cuando quieres un objetivo de volumen más silencioso estilo broadcast en lugar de un objetivo de streaming o podcast.

### ¿Se subirá mi archivo de audio?

No. GrepCut procesa tu audio en tu navegador. El archivo fuente permanece en tu dispositivo y el WAV normalizado se genera localmente.

### ¿La normalización de volumen distorsionará mi audio?

La herramienta aplica ganancia con un límite de pico de -1 dBTP para reducir el riesgo de recorte. Si tu fuente ya es muy fuerte, el limitador puede impedir alcanzar el objetivo LUFS exacto para que la exportación sea más segura.

### ¿Por qué mi archivo aún suena diferente después de igualar LUFS?

LUFS es una guía sólida de volumen, pero el tono, los graves, la compresión, el ruido de fondo y el rango dinámico aún afectan qué tan fuerte se siente tu audio. Dos archivos pueden compartir un valor LUFS y aún sentirse diferentes.

### ¿Se puede exportar MP3 después de la normalización?

Esta herramienta exporta WAV. Si necesitas otro formato de entrega, normaliza primero, luego convierte el WAV con un convertidor aparte.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre normalización de volumen en podcasts](https://www.reddit.com/r/podcasts/comments/f1fbew/editing_question_do_you_normalize_and_if_so_how/)
- [Discusión en Reddit sobre normalización de pico versus volumen percibido](https://www.reddit.com/r/audioengineering/comments/kctip9/normalising_the_volume_of_100_tracks_at_once/)
- [Guía de Spotify sobre normalización de volumen](https://support.spotify.com/us/artists/article/loudness-normalization/)
- [Recomendación ITU-R BS.1770-5 sobre volumen y pico verdadero](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1770-5-202311-I!!PDF-E.pdf)
- [Descripción general de la API Web Audio de MDN](https://developer.mozilla.org/es/docs/Web/API/Web_Audio_API)
- [Referencia de decodeAudioData de MDN para decodificación de audio en el navegador](https://developer.mozilla.org/es/docs/Web/API/BaseAudioContext/decodeAudioData)

## Normaliza Tu Audio de Forma Privada

Abre el Normalizador de Audio, elige tu objetivo LUFS y exporta un WAV limpio sin enviar tu archivo a un servidor.

## Herramientas Relacionadas

- [Eliminador de ruido de audio](https://grepcut.com/es/tools/audio-noise-remover) - Limpia el ruido de fondo antes de normalizar el volumen.
- [Creador de tonos](https://grepcut.com/es/tools/ringtone-maker) - Corta un clip breve y exporta un tono M4R o MP3.
