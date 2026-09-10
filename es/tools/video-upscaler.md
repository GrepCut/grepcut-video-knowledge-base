# Ampliador de video FSR gratuito en línea

Aumenta la resolución de tus clips con la ampliación FSR adaptativa de bordes en tu navegador.

HTML: https://grepcut.com/es/tools/video-upscaler

## Lee Esto Primero: FSR Afina Bordes, No Inventa Detalles

Establece tus expectativas antes de empezar. FSR hace que los bordes sean más nítidos al agrandar tu clip, pero en material ya suave, de baja tasa de bits o desenfocado, la mejora suele ser marginal, porque hay muy poca información de borde real para reconstruir.

FSR es un escalador espacial, no IA. No puede añadir detalles que nunca se capturaron. Reconstruir textura que no está en tu fuente necesita un modelo de superresolución IA, que es un tipo de herramienta diferente. Usa este amplificador para agrandar limpiamente y afinar bordes, no para recuperar detalles perdidos.

## Cómo Ampliar Video en Línea en tu Navegador

1. **Sube tu clip**: Arrastra un archivo MP4, MOV, WebM o MKV al área de carga.
2. **Elige 2×, 3× o 4×**: Selecciona el factor de ampliación que se ajuste a tu línea de tiempo, exportación social o diseño HD.
3. **Exporta tu MP4**: Descarga el MP4 ampliado, o ábrelo en GrepCut Studio para subtítulos, cortes y acabado.

La ampliación se ejecuta localmente en tu navegador, por lo que tu video permanece en tu dispositivo.

## Usa la Ampliación FSR Cuando tu Clip Sea Demasiado Pequeño

Si tu clip se grabó a 480p, 720p o en una ventana pequeña de captura de pantalla, puede verse pequeño dentro de una edición HD. La ampliación aumenta las dimensiones de píxeles antes de exportar, para que tu video encaje en una línea de tiempo de 1080p, una subida a YouTube o un preset social sin estiramiento manual en otro editor.

GrepCut amplía con FSR (AMD FidelityFX Super Resolution). En lugar de un estiramiento suave simple, FSR reconstruye bordes al agrandar, por lo que las líneas y contornos se mantienen más nítidos que con el escalado bicúbico. Esto lo convierte en una opción práctica para material de teléfono comprimido, clips de tutoriales y republicaciones que se exportaron demasiado pequeñas.

### Ideal para:

- **Grabaciones antiguas de teléfono**: Acerca un clip de 480p o 720p a un diseño HD con bordes más limpios antes de publicar.
- **Grabaciones de pantalla**: Haz que una ventana de captura pequeña sea más fácil de colocar en un tutorial o edición de presentación.
- **Republicaciones sociales**: Redimensiona clips verticales que volvieron de otra aplicación a una resolución más baja.

## Cómo Funciona la Ampliación FSR, y Qué Puede y No Puede Arreglar

FSR es un escalador espacial: trabaja a partir del fotograma único que tiene delante, sin vectores de movimiento, búfer de profundidad ni modelo IA. Se ejecuta en dos pasos de GPU. Primero, EASU (Edge-Adaptive Spatial Upsampling) remuestrea el fotograma de manera consciente de la dirección, detectando cómo difieren los gradientes vecinos para que los bordes se reconstruyan en lugar de simplemente difuminarse. Luego, RCAS (Robust Contrast-Adaptive Sharpening) añade un enfoque controlado que realza el detalle sin generar halos ni amplificar el ruido.

Debido a que FSR usa shaders ordinarios y nunca mira otros fotogramas, trata cada fotograma de la misma manera y mantiene tu exportación consistente. Sin embargo, no es superresolución IA. Si tu fuente está muy borrosa, muy comprimida o le faltan detalles finos, FSR puede ajustar un fotograma más grande con bordes más nítidos, pero no puede reconstruir textura que nunca se capturó.

### Bajo el capó:

- **EASU**: Remuestreo adaptativo de bordes que reconstruye bordes al agrandar, más nítido que bilineal o bicúbico.
- **RCAS**: Paso de enfoque adaptativo al contraste, aplicado automáticamente, que añade nitidez a bordes reales mientras deja intactas las áreas planas.

Para material muy suave, prueba primero una exportación corta. Si la vista previa ya se ve demasiado suave, un factor más pequeño suele verse más natural que un estiramiento fuerte a 4×.

## Cómo se Compara FSR con el Escalado Simple

| Método | Cómo escala | Resultado típico |
| --- | --- | --- |
| Vecino más cercano | Duplica el píxel más cercano. | Bordes con bloques y escalones duros. |
| Bilineal o bicúbico | Promedia los píxeles circundantes. | Más suave, pero los bordes se ven blandos. |
| FSR (EASU + RCAS) | Remuestreo adaptativo de bordes más enfoque consciente del contraste. | Bordes más limpios y nítidos sin modelo IA. |

FSR reconstruye bordes en lugar de solo suavizarlos, pero como todo método espacial, trabaja con el detalle ya presente en tu clip.

## ¿Qué Factor de Ampliación Deberías Elegir?

El factor correcto depende de cuán lejos esté tu clip del tamaño que necesitas. Factores más grandes crean más píxeles para reconstruir, por lo que una fuente suave muestra sus límites antes a 4× que a 2×.

### Elige tu factor:

- **2×**: Una primera prueba segura cuando tu clip solo necesita un aumento de tamaño moderado.
- **3×**: Útil cuando un clip pequeño necesita llenar más de un lienzo HD.
- **4×**: Ideal para clips cortos donde necesitas dimensiones máximas y puedes esperar un poco más.

Empieza con 2× si no estás seguro, luego vuelve a intentarlo con un factor mayor si tu fuente tiene suficiente detalle para aguantar.

## La Vista Previa Coincide con tu Exportación

FSR amplía y enfoca automáticamente, así que no hay nada que configurar. Elige un factor, comprueba el resultado y exporta. EASU maneja el agrandamiento adaptativo de bordes y RCAS añade un enfoque fijo y de buen gusto encima.

La vista previa de antes y después ejecuta el mismo pipeline FSR que la exportación, por lo que lo que ves es lo que llega a tu MP4. Acerca la vista previa para juzgar la nitidez de bordes antes de comprometerte con un renderizado completo.

Si la vista previa aún se ve suave después de ampliar, eso generalmente significa que el detalle no estaba en la fuente desde el principio, y un factor más bajo puede verse más natural.

## Mantén tu Video Privado Mientras Pruebas

Las herramientas de video en línea a menudo te piden subir el archivo completo antes de ver un resultado. Este amplificador se ejecuta en tu navegador, por lo que tu material no sale de tu dispositivo durante el procesamiento.

Eso es útil cuando tu clip contiene contenido de pantalla privado, material social no publicado, borradores de clientes o grabaciones de clase. Puedes probar un factor, descargar el MP4 y continuar editando sin enviar el archivo original a un servidor.

Los clips largos y las exportaciones a 4× dependen de la velocidad de tu dispositivo. Para comprobaciones rápidas, recorta el clip primero o prueba una sección corta antes de procesar el video completo.

## Ampliador de Video de un Vistazo

### Advantages

- Se ejecuta localmente en tu navegador sin subida.
- FSR reconstruye bordes, por lo que los resultados se ven más nítidos que el escalado bicúbico.
- El escalado EASU y el enfoque RCAS se aplican automáticamente, nada que configurar.
- Presets de 2×, 3× y 4× mantienen la elección simple.
- Exportación MP4 gratuita sin marca de agua.

### Disadvantages

- Es un escalador espacial, no IA, por lo que no puede inventar detalles que no se capturaron.
- Fuentes muy borrosas o muy comprimidas aún pueden verse suaves.
- Las exportaciones largas a 4× pueden tardar más en dispositivos lentos.
- Si tu navegador carece de WebGL2, recurre a un escalado bicúbico simple.

> FSR 1 no mira datos de fotogramas anteriores para mejorar su escalado, sino que estira cada imagen aislada, utilizando técnicas como la detección de bordes para ayudar a determinar la mejor manera de estirar la imagen.
>
> PCGamesN

## Preguntas Frecuentes sobre el Ampliador de Video

### ¿Puedo ampliar video en línea sin subirlo?

Sí. Tu video se procesa localmente en tu navegador, por lo que el archivo permanece en tu dispositivo.

### ¿Es FSR lo mismo que la ampliación por IA?

No. FSR es un escalador espacial que se ejecuta en shaders ordinarios y trabaja a partir de un solo fotograma. Reconstruye bordes con EASU y enfoca con RCAS, pero no usa una red neuronal, por lo que no puede inventar detalles como intenta hacer la superresolución IA.

### ¿En qué se diferencia FSR del escalado bicúbico?

El bicúbico promedia píxeles cercanos, lo que agranda el fotograma pero deja los bordes suaves. FSR observa cómo cambian los gradientes vecinos y remuestrea a lo largo de los bordes, por lo que las líneas y contornos se mantienen más nítidos, luego RCAS añade un enfoque controlado encima.

### ¿FSR hará que mi video borroso se vea nítido?

Puede hacer que los bordes se vean más limpios y añadir algo de nitidez, pero la mejora suele ser marginal en material suave, y no puede restaurar detalles faltantes de una fuente borrosa, de baja tasa de bits o desenfocada. Recuperar detalles que no están ahí necesita un amplificador IA.

### ¿Qué factor de ampliación debería usar?

Usa 2× para una primera pasada segura, 3× cuando tu clip necesite un aumento de tamaño más fuerte, y 4× para clips cortos de baja resolución donde necesites la salida más grande.

### ¿Puedo ampliar un video de 480p para una edición de 1080p?

Sí. Puedes agrandar el clip antes de colocarlo en una línea de tiempo HD. FSR mantiene los bordes más limpios que un estiramiento simple, aunque el resultado puede verse aún más suave que el material nativo de 1080p porque el original tiene menos píxeles.

### ¿Necesito ajustar alguna configuración?

No. FSR amplía con EASU y enfoca con RCAS automáticamente, así que solo eliges un factor y exportas. La vista previa de antes y después usa el mismo pipeline que la exportación.

### ¿Qué formatos de video puedo importar y hay marca de agua?

Puedes importar archivos MP4, MOV, WebM y MKV, y exportar tu MP4 ampliado sin marca de agua.

## Fuentes y lecturas adicionales

- [Resumen de AMD GPUOpen de FidelityFX Super Resolution 1 (EASU y RCAS)](https://gpuopen.com/fidelityfx-superresolution/)
- [Manual técnico de escalado espacial FSR 1 de AMD GPUOpen](https://gpuopen.com/manuals/fidelityfx_sdk/techniques/super-resolution-spatial/)
- [FidelityFX Super Resolution 1.0 desmitificado (recorrido de shader)](https://jntesteves.github.io/shadesofnoice/graphics/shaders/upscaling/2021/09/11/amd-fsr-demystified.html)
- [Tom's Hardware: probando rendimiento y calidad de imagen de FSR](https://www.tomshardware.com/news/amd-fidelityfx-super-resolution-fsr-performance-tested)
- [Hilo del foro guru3D: FSR 1 es genial para lo que es](https://forums.guru3d.com/threads/fsr-1-is-great-actually-for-what-it-is.453779/)
- [Hilo de Reddit sobre por qué el material escalado puede verse borroso](https://www.reddit.com/r/premiere/comments/1asd5id/scaling_up_video_to_a_higher_resolution_makes_it/)
- [Resumen de Wikipedia sobre métodos de escalado de imágenes](https://en.wikipedia.org/wiki/Image_scaling)

## ¿Terminaste de Ampliar? Pule la Edición Completa

Abre tu MP4 ampliado en GrepCut Studio para cortar la línea de tiempo, añadir subtítulos, ajustar el aspecto y exportar el video final en tu navegador.

## Herramientas Relacionadas

- [Redimensionar Video](https://grepcut.com/es/tools/resize-video) - escala tu clip por porcentaje.
- [Cambiar Velocidad de Video](https://grepcut.com/es/tools/change-video-speed) - ralentiza o acelera tu material.
- [Desenfocar Video](https://grepcut.com/es/tools/blur-video) - suaviza fondos u oculta áreas sensibles.
