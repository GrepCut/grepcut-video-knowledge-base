# Rotar video en línea

Gire la grabación de costado a vertical o voltee su clip para publicaciones en redes sociales. Procesado localmente en su navegador: sin carga, sin marca de agua.

HTML: https://grepcut.com/es/tools/rotate-video

## Cómo rotar un video en tu navegador

1. **Añade tu video**: Arrastra tu MP4, MOV, WebM, MKV o M4V a la herramienta, o haz clic para examinar. Tu archivo permanece en tu dispositivo mientras el navegador prepara la vista previa.
2. **Elige el ángulo**: Selecciona 90° en sentido horario, 180° o 90° en sentido antihorario. Usa la vista previa para verificar que tu clip de móvil esté vertical antes de exportar.
3. **Selecciona el modo de exportación**: Usa Social-ready cuando quieras que la rotación quede grabada en los píxeles, o Fast remux cuando solo necesites cambiar el indicador de rotación del MP4.
4. **Descarga tu MP4**: Haz clic en Rotar para exportar tu video corregido como MP4. También puedes abrir el clip en GrepCut Studio si necesitas recortar, redimensionar, añadir subtítulos o editar la línea de tiempo.

¿Necesitas algo más que rotar? Abre tu clip en [GrepCut Studio](/) y continúa editando en el navegador.

## Por qué tu video del móvil se ve lateral

Un video del móvil puede verse correcto en tu galería pero lateral en otra aplicación porque el archivo puede almacenar un indicador de rotación en lugar de píxeles verticales. Cuando un reproductor o plataforma respeta ese indicador, tu clip se ve bien. Cuando lo ignora, el video aparece rotado aunque la grabación en sí no esté dañada.

GrepCut te ofrece dos soluciones para ese problema. El modo Social-ready rota físicamente los fotogramas y elimina el indicador de rotación, siendo la opción más segura antes de publicar. Fast remux mantiene el flujo de video original y actualiza los metadatos de rotación, lo cual es más rápido pero depende de que la siguiente aplicación lea correctamente el indicador.

### Úsalo cuando:

- **Tu clip del móvil está lateral**: Endereza grabaciones verticales u horizontales antes de subirlas.
- **Tu video está al revés**: Rota 180° cuando la orientación de la cámara fue incorrecta durante la grabación.
- **Tu aplicación ignora los metadatos de rotación**: Graba la rotación en los píxeles para que el resultado no dependa de un indicador oculto.
- **Necesitas una exportación rápida a MP4**: Guarda un MP4 corregido sin abrir un editor de video de escritorio.

Si vas a publicar en Instagram, TikTok, YouTube u otra plataforma que pueda procesar el archivo de nuevo, elige **Social-ready** para obtener el resultado más predecible.

## Listo para redes vs remux rápido

| Necesidad | Social-ready | Fast remux |
| --- | --- | --- |
| Qué cambia | Rota los fotogramas reales y elimina el indicador de rotación | Mantiene los fotogramas originales y actualiza los metadatos de rotación del MP4 |
| Velocidad | Más lento porque el video se recodifica a H.264 | Casi instantáneo porque los paquetes de video comprimido se copian |
| Calidad | Exportación H.264 de alta calidad, pero sigue siendo una recodificación | Idéntica al flujo de video original |
| Mejor para subir a redes sociales | Mejor opción cuando la siguiente aplicación puede ignorar los metadatos de rotación | Funciona solo cuando la siguiente aplicación respeta el indicador de rotación |
| Resultado | Píxeles verticales en un archivo MP4 | Mismos píxeles con una instrucción de rotación corregida |

Ambos modos se ejecutan localmente en tu navegador. Tu video original no se sube y la exportación no tiene marca de agua.

## Cuándo deberías recodificar en lugar de remux

Fast remux es útil cuando quieres una corrección local rápida y sabes que el siguiente reproductor lee los metadatos de rotación del MP4. Puede ser la opción adecuada para previsualizar, archivar o enviar un archivo a una aplicación que ya maneje correctamente los indicadores de rotación.

Social-ready es mejor cuando el clip se va a subir, comprimir de nuevo o abrir en diferentes dispositivos. Al escribir píxeles verticales en el MP4, eliminas la incertidumbre. Tu exportación puede tardar más, pero el archivo es más fácil de mostrar correctamente para las plataformas sociales y los reproductores básicos.

### Una regla simple:

Si el video es para publicar, elige **Social-ready**. Si el video es para tu propio dispositivo y quieres la corrección más rápida posible, prueba **Fast remux**.

## Rotar Video de un vistazo

### Advantages

- Procesamiento privado sin subida al servidor.
- Opciones de rotación de 90°, 180° y 270°.
- Exportación MP4 Social-ready para una orientación predecible.
- Opción Fast remux cuando solo necesitas corregir metadatos.
- Exportación gratuita sin marca de agua.

### Disadvantages

- El modo Social-ready recodifica el video, por lo que la exportación tarda más que el remux.
- Fast remux depende de que la siguiente aplicación respete los metadatos de rotación.
- Solo se admiten rotaciones en ángulo recto, no ángulos arbitrarios.
- Requiere un navegador moderno con soporte para WebCodecs.

> observado por algunos reproductores y no por otros
>
> Discusión de Stack Overflow sobre metadatos de rotación en MP4

## Rotar Video - Preguntas Frecuentes

### ¿Se puede rotar un video sin subirlo?

Sí. GrepCut ejecuta el proceso de rotación en tu navegador, por lo que tu archivo permanece en tu dispositivo en lugar de subirse a un servidor.

### ¿Por qué mi MP4 se ve lateral en una aplicación pero correcto en otra?

Tu MP4 puede contener metadatos de rotación. Algunos reproductores leen esa instrucción y rotan el video durante la reproducción, mientras que otras aplicaciones la ignoran. Usa el modo **Social-ready** cuando quieras que el MP4 exportado contenga píxeles verticales en lugar de depender de metadatos.

### ¿Deberías usar Social-ready o Fast remux?

Usa **Social-ready** cuando planees publicar el clip en línea o enviarlo a una aplicación que pueda ignorar los indicadores de rotación. Usa **Fast remux** cuando quieras la exportación más rápida y el siguiente reproductor probablemente respete los metadatos de rotación del MP4.

### ¿Rotar tu video reducirá la calidad?

Fast remux mantiene el flujo de video original sin cambios, por lo que el flujo de video permanece idéntico. El modo Social-ready recodifica a H.264 para que la rotación quede grabada en los píxeles, lo cual es más fiable para publicar pero tarda más.

### ¿Qué formatos de video se pueden rotar?

Puedes añadir MP4, MOV, WebM, MKV, M4V y la mayoría de formatos de video comunes. GrepCut exporta el resultado rotado como MP4.

### ¿El audio se mantendrá sincronizado después de la rotación?

Sí. La rotación no cambia la velocidad de reproducción. El audio se copia sin pérdida si ya es AAC, o se recodifica a AAC para una amplia compatibilidad con MP4.

### ¿Se puede rotar con un ángulo personalizado como 12°?

No. Esta herramienta está diseñada para correcciones en ángulo recto: 90° en sentido horario, 180° y 90° en sentido antihorario. Para grabaciones laterales de móvil, esas suelen ser las correcciones que necesitas.

### ¿Por qué GrepCut necesita un navegador moderno?

La exportación Social-ready depende de funciones de procesamiento de video del navegador como WebCodecs. Si tu navegador no soporta las API necesarias, prueba con un navegador basado en Chromium actualizado.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre grabación accidental en modo vertical](https://www.reddit.com/r/VideoEditing/comments/xryq3n/i_accidentally_filmed_my_videos_in_portrait_mode/)
- [Pregunta en Reddit sobre rotar sin recodificar](https://www.reddit.com/r/VideoEditing/comments/uuw62f/automatically_rotate_video_without_actually/)
- [Explicación en Super User sobre metadatos de rotación en videos de iPhone](https://superuser.com/questions/564233/iphone-recorded-videos-getting-rotated-on-windows-systems)
- [Discusión en Stack Overflow sobre indicadores de rotación en MP4](https://stackoverflow.com/questions/69386275/mp4-and-rotation-remove-flags-but-set-rotation)
- [Guía de MDN sobre la API WebCodecs](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [Especificación de WebCodecs del W3C](https://www.w3.org/TR/webcodecs/)

## ¿Terminaste de rotar? Crea la edición completa

Abre GrepCut Studio para recortar, redimensionar, añadir subtítulos, añadir música y finalizar tu edición de video en el navegador.

## Herramientas relacionadas

- [Recortar Video](https://grepcut.com/es/tools/crop-video) - recorta tu fotograma a una región o relación de aspecto.
- [Redimensionar Video](https://grepcut.com/es/tools/resize-video) - escala tu clip por porcentaje.
- [Recortador de Video](https://grepcut.com/es/tools/video-trimmer) - corta tu clip antes o después de rotar.
