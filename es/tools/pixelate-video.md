# Pixelar Video Online

Aplica un efecto de mosaico a cada fotograma de tu clip. Todo se procesa localmente en tu dispositivo: sin subidas, sin marcas de agua, sin cuenta.

HTML: https://grepcut.com/es/tools/pixelate-video

## Cómo pixelar un video en tu navegador

1. **Sube tu archivo de video**: Arrastra tu clip MP4, MOV, WebM o MKV al área de carga.
2. **Elige el tamaño del bloque de píxeles**: Selecciona un tamaño de bloque más pequeño para un mosaico más fino o uno más grande para un efecto más pixelado.
3. **Pixelar y exportar**: Haz clic en Pixelar y exportar para renderizar el mosaico localmente y descargar el MP4.

Tu video se procesa en tu navegador, por lo que puedes añadir un efecto de pixelado sin subir el archivo a un servidor.

## Cuándo tiene sentido un efecto de mosaico en todo el fotograma

Pixelar un video convierte cada fotograma en bloques cuadrados visibles. Es adecuado cuando buscas un estilo visual retro, una vista previa con privacidad o un efecto de censura simple en todo el clip.

Esta herramienta aplica el mosaico a todo el fotograma de principio a fin. Si solo necesitas ocultar una cara, matrícula, mensaje de chat u objeto pequeño, usa [Desenfocar región de video](/tools/blur-region-video) para que el resto del clip se mantenga nítido.

### Usa pixelado cuando quieras que la edición sea evidente

- **Ediciones estilizadas**: Puedes hacer que un clip parezca grabación de videojuego de baja resolución, arte glitch o un segmento censurado de televisión.
- **Vistas previas privadas**: Puedes hacer que todo el fotograma sea más difícil de leer antes de compartir un borrador o clip de referencia.
- **Efecto consistente**: Como el mosaico cubre todo el fotograma, no necesitas rastrear un sujeto en movimiento ni ajustar una máscara.

## Qué cambia el tamaño del bloque de píxeles

El tamaño del bloque controla lo tosco que se ve el mosaico. Los bloques más pequeños conservan más las formas y el movimiento originales, mientras que los más grandes hacen que el fotograma sea más abstracto.

Si tu objetivo es el estilo, comienza con un tamaño de bloque mediano y previsualiza el resultado. Si tu objetivo es ocultar por privacidad, elige un tamaño de bloque más grande, pero no trates el pixelado como una garantía legal o de seguridad para material sensible.

Para material muy sensible, la edición más segura suele ser eliminar, recortar o evitar compartir el área identificable en lugar de confiar en cualquier efecto visual.

## Pixelado vs Desenfoque vs Desenfoque de región

| Efecto | Ideal para | Cómo cambia tu video |
| --- | --- | --- |
| Pixelar Video | Estilo mosaico en todo el fotograma o vistas previas con privacidad | Agrupa todo el fotograma en bloques cuadrados con un tamaño de bloque ajustable |
| Desenfocar Video | Suavizar todo el clip | Aplica un desenfoque suave en cada fotograma con intensidad ajustable |
| Desenfocar Región de Video | Ocultar un área rectangular | Apunta solo a la región seleccionada mientras el resto del video permanece visible |

Si quieres un aspecto pixelado en todas partes, usa Pixelar Video. Si quieres una neblina suave en todas partes, usa [Desenfocar Video](/tools/blur-video). Si solo necesitas ocultar un área, usa [Desenfocar Región de Video](/tools/blur-region-video).

## Pixelado de video privado y local

GrepCut procesa tus fotogramas localmente en el navegador. Tu archivo se decodifica, pixela, renderiza y exporta en tu dispositivo en lugar de subirse a los servidores de GrepCut.

Ese flujo de trabajo local es útil cuando tu clip contiene imágenes personales, material de trabajo, detalles de ubicación o cualquier cosa que prefieras no enviar a un editor en línea solo para añadir un efecto de mosaico simple.

## Ventajas de Pixelar Video

### Advantages

- Tu archivo permanece en tu dispositivo porque el procesamiento es 100% del lado del cliente.
- Puedes exportar gratis sin marca de agua.
- Puedes elegir tamaños de bloque predefinidos desde un mosaico sutil hasta una pixelación extrema.
- Los clips más largos pueden usar renderizado paralelo multinúcleo.

### Disadvantages

- El efecto cubre todo el fotograma, no un objeto o rostro seleccionado.
- Los videos grandes pueden tardar más porque cada fotograma debe decodificarse, procesarse y exportarse localmente.
- La pixelación puede reducir el detalle, pero no debe tratarse como una garantía completa de anonimato para material sensible.

> A diferencia de los desenfoques, un efecto de mosaico destruye efectivamente los datos sobre los que se aplica.
>
> Discusión en Reddit r/VideoEditing

## Preguntas frecuentes sobre Pixelar Video

### ¿Se puede pixelar un video sin subirlo?

Sí. GrepCut ejecuta el efecto de pixelado dentro de tu navegador, por lo que tu video permanece en tu dispositivo y no se sube a los servidores de GrepCut.

### ¿Se puede pixelar solo un rostro u objeto?

No con esta herramienta. Pixelar Video aplica el mosaico a todo el fotograma. Si necesitas ocultar solo un área rectangular, usa [Desenfocar Región de Video](/tools/blur-region-video).

### ¿Cuál es la diferencia entre desenfoque y pixelado?

El desenfoque suaviza el detalle en una neblina homogénea. El pixelado agrupa la imagen en bloques nítidos. Elige pixelado cuando quieras un efecto de mosaico visible, y desenfoque cuando quieras un aspecto más suave.

### ¿Se puede ajustar la intensidad del pixelado?

Sí. Puedes elegir tamaños de bloque predefinidos desde 5px hasta 1000px. Los bloques más pequeños crean un mosaico más fino, mientras que los más grandes hacen que el video sea mucho más abstracto.

### ¿El video exportado tendrá marca de agua?

No. Las exportaciones de GrepCut son gratuitas y sin marca de agua.

### ¿Por qué pixelar un video lleva tiempo?

Cada fotograma debe decodificarse, transformarse en bloques y renderizarse de nuevo. Los clips más largos, resoluciones más grandes y procesamiento más pesado pueden llevar más tiempo, especialmente porque el trabajo se realiza localmente en tu dispositivo.

### ¿Es suficiente el pixelado para trabajos de privacidad sensibles?

El pixelado puede hacer que los detalles sean más difíciles de leer, especialmente con bloques grandes, pero no debes confiar en ningún efecto visual como garantía completa para material sensible. Si la exposición fuera perjudicial, recorta, elimina o evita compartir ese contenido.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre desenfoque, mosaico y reversibilidad](https://www.reddit.com/r/VideoEditing/comments/1ttqwpd/can_facial_blur_be_removed_by_other_people/)
- [Hilo de Reddit sobre elegir herramientas de desenfoque o pixelado para privacidad en video](https://www.reddit.com/r/poledancing/comments/1hhhxdo/best_apps_for_blurring_others_in_videos/)
- [Discusión en Super User sobre desenfocar solo una parte de un video con FFmpeg](https://superuser.com/questions/901099/ffmpeg-apply-blur-over-face)
- [Referencia de MDN para imageSmoothingEnabled en canvas](https://developer.mozilla.org/es/docs/Web/API/CanvasRenderingContext2D/imageSmoothingEnabled)
- [Descripción general de la API WebCodecs en MDN](https://developer.mozilla.org/es/docs/Web/API/WebCodecs_API)
- [Guía de Chrome Developers para procesamiento de video con WebCodecs](https://developer.chrome.com/docs/web-platform/best-practices/webcodecs)

## Pixelá tu video de forma privada

Abrí GrepCut, arrastrá tu clip, elegí un tamaño de bloque de mosaico y exportá un MP4 pixelado sin subir tu archivo.

## Herramientas relacionadas

- [Blur Video Region](https://grepcut.com/es/tools/blur-region-video) - oculta un área rectangular en lugar de todo el encuadre.
- [Blur Video](https://grepcut.com/es/tools/blur-video) - aplica un desenfoque suave a todo el clip.
- [Video Trimmer](https://grepcut.com/es/tools/video-trimmer) - quita los tramos que no quieras antes o después de pixelar.
