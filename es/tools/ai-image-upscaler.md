# Ampliador de imágenes AI gratuito en línea

Mejora fotos y gráficos con superresolución Real-CUGAN que se ejecuta localmente en tu dispositivo. Sin carga, sin marca de agua, o usa el modo Lienzo Rápido para exportaciones rápidas 3×.

HTML: https://grepcut.com/es/tools/ai-image-upscaler

## Cómo ampliar una imagen con IA en tu navegador

1. **Arrastra tu imagen**: Sube un archivo JPG, PNG o WebP desde tu dispositivo.
2. **Elige el modo de ampliación**: Usa Real-CUGAN IA para superresolución 2x o 4x, o Canvas rápido para escalado 2x, 3x y 4x veloz.
3. **Exporta la imagen más grande**: Descarga tu imagen ampliada en PNG o JPEG sin marca de agua.

Tu imagen se procesa localmente en tu navegador. Nada se sube a GrepCut. ¿Necesitas ampliar clips en lugar de imágenes fijas? Prueba el [Ampliador de vídeo](/tools/video-upscaler).

## Cuándo ayuda la ampliación con IA a tu imagen

Si tu foto, escaneo, captura de pantalla o exportación social pequeña es demasiado diminuta para un diseño, necesitas más píxeles antes de recortar, imprimir o reutilizarla. La superresolución con IA hace más que estirar la imagen: predice bordes y texturas más nítidos a partir de la entrada de baja resolución.

El modo IA de GrepCut ejecuta Real-CUGAN localmente con TensorFlow.js. Esto significa que puedes ampliar una imagen sin enviar el archivo fuera de tu dispositivo, crear una cuenta ni añadir una marca de agua.

### Úsalo cuando quieras un archivo más grande sin salir de tu navegador:

- **Fotos pequeñas**: Aumenta la resolución antes de recortar más ajustado o colocar la imagen en un diseño más grande.
- **Ilustraciones y arte anime**: Real-CUGAN fue creado para superresolución de imágenes y es especialmente relevante para detalles dibujados, bordes y obras de arte estilizadas.
- **Capturas de pantalla y miniaturas**: Haz que las capturas de interfaz, imágenes de vista previa y capturas de documentación sean más fáciles de reutilizar en tamaños más grandes.

## Modo IA vs Modo Canvas rápido

| Modo | Ideal para | Qué esperar |
| --- | --- | --- |
| Real-CUGAN IA | Ampliación 2x o 4x cuando importa la calidad del detalle | Reconstrucción más nítida, procesamiento más lento y mejores resultados en un navegador moderno con WebGPU o WebGL |
| Canvas rápido | Exportaciones rápidas a 2x, 3x o 4x | Escalado rápido del navegador sin recuperación de detalles mediante red neuronal |
| Verificación de tamaño original | Entradas muy ruidosas, comprimidas o borrosas | La ampliación puede hacer más visibles los defectos existentes, así que inspecciona el resultado antes de usarlo en impresiones o listados |

Si necesitas dimensiones exactas en píxeles en lugar de un multiplicador, usa el [Redimensionador de imágenes](/tools/resize-video) después de ampliar.

## Por qué la ampliación 4x no es magia

Una ampliación 4x da a tu archivo muchos más píxeles, pero no puede recuperar información que nunca fue capturada. Si tu imagen original tiene texto ilegible, bloques JPEG pesados o desenfoque de movimiento, la IA puede afilar la forma del problema en lugar de revelar el detalle real.

Para obtener resultados más limpios, parte de la versión menos comprimida que tengas. Si estás comparando modos, exporta ambas versiones (IA y Canvas rápido) y elige la que se vea más natural para tu imagen.

Esto es más importante para rostros, texto y detalles de productos, donde un resultado de aspecto más nítido no siempre es un resultado más preciso.

## Ampliador de imágenes con IA de un vistazo

### Advantages

- Funciona en tu navegador sin subir imágenes.
- Modo IA Real-CUGAN para superresolución 2x y 4x.
- Modo Canvas rápido compatible con escalado 2x, 3x y 4x.
- Exportación gratuita sin marca de agua.

### Disadvantages

- El modo IA puede ser más lento en imágenes grandes.
- Fuentes muy borrosas o comprimidas pueden mostrar artefactos.
- El modo IA necesita un navegador moderno con soporte WebGPU o WebGL.

> los resultados dependen de la foto y la resolución del archivo original
>
> Reddit r/photography

## Preguntas frecuentes sobre el ampliador de imágenes con IA

### ¿Se puede ampliar una imagen sin subirla?

Sí. GrepCut procesa tu imagen localmente en tu navegador, incluido el modo IA. Tu archivo no sale de tu dispositivo.

### ¿Es esto verdadera ampliación con IA o solo redimensionado?

El modo IA usa superresolución Real-CUGAN. El modo Canvas rápido es diferente: usa el escalado Canvas del navegador para exportaciones rápidas 2x, 3x y 4x sin reconstrucción mediante red neuronal.

### ¿Deberías usar ampliación IA 2x o 4x?

Usa 2x cuando necesites un aumento de resolución moderado con menos artefactos. Usa 4x cuando la fuente sea lo suficientemente limpia y necesites una imagen mucho más grande para diseño, preparación de impresión o recorte cercano.

### ¿La ampliación con IA arreglará texto o rostros borrosos?

Puede hacer que los bordes se vean más nítidos, pero no puede garantizar detalles faltantes precisos. Si tu texto o rostro original está demasiado borroso, inspecciona el resultado cuidadosamente antes de tratarlo como factual o listo para imprimir.

### ¿Qué formatos de imagen se pueden subir?

Puedes subir imágenes JPG, PNG o WebP. La exportación se guarda como PNG o JPEG dependiendo de lo que el navegador pueda preservar para tu archivo.

### ¿Por qué el modo IA es más lento que el Canvas rápido?

El modo IA ejecuta una red neuronal en tu dispositivo, por lo que el procesamiento depende del tamaño de tu imagen, navegador y soporte de GPU. El modo Canvas rápido omite el modelo IA, por lo que es más rápido pero menos detallado.

### ¿Se puede ampliar arte anime o imágenes de juegos?

Sí. Real-CUGAN es especialmente relevante para ilustraciones, arte estilo anime y bordes gráficos nítidos. Para pixel art, compara IA con Canvas rápido porque algunas obras se ven mejor cuando se preserva la estructura de píxeles original.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre cómo la ampliación con IA depende de la imagen fuente](https://www.reddit.com/r/photography/comments/bml58t/whats_your_opinion_on_upscaling_photos_with_ai/)
- [Hilo de Reddit sobre Real-CUGAN para webtoons y arte estilo cómic](https://www.reddit.com/r/StableDiffusion/comments/1jcuxna/upscaling_models_recommendations_for_a_newbie/)
- [README del proyecto Real-CUGAN](https://github.com/bilibili/ailab/blob/main/Real-CUGAN/README_EN.md)
- [Guía oficial de TensorFlow.js sobre entornos de navegador y plataforma](https://www.tensorflow.org/js/guide/platform_environment)
- [Documentación de MDN sobre suavizado de imágenes en Canvas](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/imageSmoothingEnabled)
- [Notas del modelo Real-CUGAN TensorFlow.js en Hugging Face](https://huggingface.co/shammisw/real-cugan-tensorflowjs)

## ¿Terminaste de ampliar? Completa la edición completa

Abre GrepCut Studio cuando quieras combinar tu imagen ampliada con edición de línea de tiempo, subtítulos, LUTs y exportación basada en navegador.

## Herramientas relacionadas

- [Video Upscaler](https://grepcut.com/es/tools/video-upscaler) - amplía clips con interpolación en el navegador.
- [Resize Video](https://grepcut.com/es/tools/resize-video) - escala el vídeo a dimensiones exactas para formatos sociales.
