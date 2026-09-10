# Desenfoque automático de rostros en video

MediaPipe BlazeFace detecta rostros fotograma a fotograma y aplica un desenfoque de privacidad. Anonimiza multitudes, entrevistas o material de archivo sin enmascaramiento manual.

HTML: https://grepcut.com/es/tools/face-blur

## Para obtener los mejores resultados

Auto Face Blur funciona mejor con videos de menos de un minuto y con movimiento constante de cámara o sujeto. Los clips con paneos repentinos, giros rápidos de cabeza o movimiento abrupto tienen más probabilidades de perder rostros entre fotogramas, así que revisa la exportación antes de compartir material sensible.

## Cómo difuminar rostros en tu video automáticamente

1. **Elige tu archivo de video**: Arrastra material de una entrevista, evento, aula, grabación de pantalla o espacio público.
2. **Deja que la detección facial se ejecute**: MediaPipe BlazeFace detecta rostros en tu dispositivo, fotograma a fotograma, sin enviar tu material a un servidor en la nube.
3. **Revisa el difuminado**: Verifica que todos los rostros visibles que necesitas ocultar estén cubiertos, especialmente en tomas concurridas, de movimiento rápido o con poca luz.
4. **Exporta tu MP4**: Descarga un video con difuminado gaussiano de privacidad aplicado a cada rostro detectado.

Como el procesamiento ocurre en tu navegador, tu video permanece en tu dispositivo mientras preparas una exportación que respeta la privacidad y es fácil de compartir.

## Por qué el difuminado automático de rostros te ahorra el enmascarado manual

Si alguna vez has intentado ocultar un rostro en movimiento con una máscara manual, conoces la parte tediosa: la máscara debe seguir el rostro a lo largo de la toma. Eso se vuelve más difícil cuando tu sujeto gira, camina detrás de otra persona o se mueve a través de un encuadre concurrido.

Auto Face Blur está diseñado para ese trabajo repetitivo de privacidad. Subes el clip, el navegador detecta rostros con IA local y GrepCut aplica difuminado a las áreas de rostros detectados para que no tengas que ajustar fotogramas clave manualmente.

### Úsalo cuando necesites privacidad antes de compartir

- **Entrevistas callejeras**: Oculta transeúntes antes de publicar un clip grabado en un lugar público.
- **Grabaciones de aulas o talleres**: Reduce la exposición de identidad antes de compartir una grabación con un grupo más amplio.
- **Videos de resumen de eventos**: Difumina rostros en tomas multitudinarias donde no quieras que todas las personas sean reconocibles.
- **Clips de creadores**: Protege a desconocidos, menores o invitados de fondo antes de publicar videos cortos.

Esta herramienta se centra en rostros. Si necesitas censurar un letrero, placa, pantalla, insignia u otra área fija, usa [Blur Region](/tools/blur-region-video) en su lugar.

## Auto Face Blur vs Enmascarado Manual vs Herramientas en la Nube

| Método | Mejor para | Compromiso |
| --- | --- | --- |
| Auto face blur en GrepCut | Ocultar rápidamente rostros detectados en tu navegador | Aún necesitas revisar el resultado para ver si hay rostros omitidos o parcialmente visibles |
| Seguimiento manual de máscara | Control preciso sobre un rostro o un área personalizada | Puede que necesites ajustar máscaras fotograma a fotograma cuando el movimiento cambia |
| Herramientas de anonimización en la nube | Flujos de trabajo del lado del servidor o revisiones en equipo | Tu material generalmente sale de tu dispositivo, lo que puede no ser adecuado para material sensible |

Elige el flujo de trabajo que coincida con tu nivel de riesgo. Para material privado o sensible al GDPR, el procesamiento local en el navegador te ayuda a evitar subir video sin procesar a un servidor de terceros.

## Qué puede y qué no puede garantizar la detección facial

La detección facial funciona mejor cuando los rostros son visibles, de tamaño razonable y no están muy ocultos. Un rostro que está girado, cubierto por una mano, recortado en el borde o difuminado por el movimiento puede ser más difícil de detectar en cada fotograma.

Antes de publicar, revisa tu exportación y busca rostros omitidos, reflejos, etiquetas con nombre, placas de matrícula, pantallas, voces u otros identificadores. Difuminar rostros reduce la identificación visual, pero no elimina automáticamente todos los riesgos de privacidad en un video.

### Para compartir material sensible, revisa más que el rostro

- **Rostros pequeños**: Los rostros pequeños en el fondo pueden ser más difíciles de detectar de manera consistente.
- **Movimiento rápido**: El desenfoque de movimiento y los paneos rápidos de cámara pueden hacer que la detección sea menos fiable.
- **Otros identificadores**: Un difuminado facial no ocultará nombres, insignias, tatuajes, placas, pantallas ni audio hablado.

Si tu clip incluye material sensible legal, médico, laboral, escolar o del sector público, trata esto como una ayuda de edición y confirma tus obligaciones de privacidad antes de distribuirlo.

## Ventajas y límites del difuminado facial en el navegador

### Advantages

- Tu video sin procesar permanece en tu dispositivo durante el procesamiento
- Se pueden difuminar múltiples rostros detectados en el mismo fotograma
- Evitas instalar un editor de video completo para una tarea simple de privacidad
- El MP4 exportado está listo para compartir después de revisarlo

### Disadvantages

- La detección facial puede omitir rostros ocultos, pequeños, de perfil o en movimiento rápido
- Se dirige automáticamente a rostros, no a placas de matrícula, pantallas o texto
- Los videos grandes o largos dependen del rendimiento de tu dispositivo y navegador
- Un difuminado gaussiano no es una garantía legal completa de anonimización por sí mismo

## Preguntas frecuentes sobre Face Blur

### ¿Puedes difuminar múltiples rostros en un solo video?

Sí. GrepCut aplica difuminado a cada rostro que detecta en cada fotograma, por lo que un plano multitudinario o un clip de entrevista puede tener más de un rostro difuminado.

### ¿Se subirá tu video?

No. La detección facial y el renderizado se ejecutan localmente en tu navegador, por lo que tu video sin procesar no necesita salir de tu dispositivo.

### ¿Puedes difuminar solo un rostro seleccionado?

Esta herramienta está diseñada para difuminar rostros detectados automáticamente. Si necesitas apuntar solo a un área fija específica, usa [Blur Region](/tools/blur-region-video).

### ¿Difuminará rostros que se mueven?

Sí, la herramienta analiza fotogramas y aplica difuminado donde se detectan rostros a medida que se mueven. Aún debes revisar la exportación, porque el movimiento rápido, la oclusión o los rostros muy pequeños pueden afectar la detección.

### ¿Puedes difuminar placas de matrícula o texto con esta herramienta?

No automáticamente. Auto Face Blur se centra en rostros. Para placas, letreros, pantallas u otras áreas, usa [Blur Region](/tools/blur-region-video) o [Pixelate Video](/tools/pixelate-video).

### ¿Es suficiente el difuminado facial para material sensible al GDPR?

Puede ayudar a reducir la identificación, especialmente porque tu video permanece local, pero no es un consejo legal ni una garantía completa de anonimización. Verifica el video exportado en busca de otros identificadores antes de compartirlo.

### ¿Por qué podría omitirse un rostro?

Un rostro puede ser demasiado pequeño, estar girado, parcialmente cubierto, recortado por el encuadre o difuminado por el movimiento. Si el clip es sensible, revisa la exportación completa antes de publicarlo.

## Fuentes y lecturas adicionales

- [Discusión en Reddit sobre el seguimiento práctico de difuminado facial en editores de video](https://www.reddit.com/r/VideoEditing/comments/12o8bpq/good_ways_to_blur_faces_in_video/)
- [Hilo de Super User sobre difuminar un rostro en movimiento con coordenadas cambiantes](https://superuser.com/questions/1704283/how-to-apply-an-ffmpeg-filter-to-a-moving-object)
- [Hilo de Reddit solicitando aplicaciones de difuminado facial automático](https://www.reddit.com/r/VideoEditing/comments/1d8cx08/looking_for_apps_that_automatically_blurs_faces/)
- [Guía de Google MediaPipe Face Detector para web](https://developers.google.com/edge/mediapipe/solutions/vision/face_detector/web_js)
- [Descripción general de MediaPipe Face Detection basada en BlazeFace](https://mediapipe.readthedocs.io/en/latest/solutions/face_detection.html)
- [Guía de la ICO sobre anonimización efectiva y enmascaramiento de material de video](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/data-sharing/anonymisation/how-do-we-ensure-anonymisation-is-effective/)

## Difumina rostros sin subir tu video

Abre GrepCut, arrastra tu clip y crea un MP4 con rostros difuminados directamente en tu navegador. Tu material permanece local mientras preparas una exportación que respeta la privacidad.

## Herramientas relacionadas

- [Blur Region](https://grepcut.com/es/tools/blur-region-video) - oculta manualmente un área fija como una placa, letrero o pantalla.
- [Pixelate Video](https://grepcut.com/es/tools/pixelate-video) - pixeliza todo el clip con un mosaico de bloques.
- [Video Trimmer](https://grepcut.com/es/tools/video-trimmer) - corta partes privadas o irrelevantes antes de exportar.
