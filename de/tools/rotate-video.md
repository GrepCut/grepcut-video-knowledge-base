# Video online drehen

Drehen Sie seitliche Handyaufnahmen hochkant oder kippen Sie Ihren Clip für Social-Media-Beiträge. Die Verarbeitung erfolgt lokal in Ihrem Browser - kein Hochladen, kein Wasserzeichen.

HTML: https://grepcut.com/de/tools/rotate-video

## So drehen Sie ein Video im Browser

1. **Video hinzufügen**: Ziehen Sie Ihre MP4-, MOV-, WebM-, MKV- oder M4V-Datei in das Tool oder klicken Sie zum Durchsuchen. Ihre Datei bleibt auf Ihrem Gerät, während der Browser die Vorschau vorbereitet.
2. **Winkel wählen**: Wählen Sie 90° im Uhrzeigersinn, 180° oder 90° gegen den Uhrzeigersinn. Nutzen Sie die Vorschau, um zu prüfen, ob Ihr Handyclip vor dem Export hochkant ausgerichtet ist.
3. **Exportmodus auswählen**: Verwenden Sie „Social-ready“, wenn die Drehung in die Pixel eingebrannt werden soll, oder „Fast remux“, wenn nur das MP4-Dreh-Flag geändert werden muss.
4. **MP4 herunterladen**: Klicken Sie auf „Drehen“, um Ihr korrigiertes Video als MP4 zu exportieren. Sie können den Clip auch in GrepCut Studio öffnen, falls Sie Zuschnitt, Größenänderung, Untertitel oder Timeline-Bearbeitungen benötigen.

Benötigen Sie mehr als nur Drehung? Öffnen Sie Ihren Clip in [GrepCut Studio](/) und bearbeiten Sie ihn weiter im Browser.

## Warum Ihr Handy-Video seitlich aussieht

Ein Handy-Video kann in Ihrer Galerie korrekt aussehen, aber in einer anderen App seitlich erscheinen, weil die Datei möglicherweise ein Dreh-Flag speichert, anstatt die Pixel hochkant zu speichern. Wenn ein Player oder Uploader dieses Flag respektiert, sieht Ihr Clip gut aus. Wenn er es ignoriert, erscheint Ihr Video gedreht, obwohl die Aufnahme selbst nicht fehlerhaft ist.

GrepCut bietet zwei Lösungen für dieses Problem. Der Modus „Social-ready“ dreht die Frames physisch und entfernt das Dreh-Flag - die sicherere Wahl vor dem Posten. „Fast remux“ behält den ursprünglichen Videostream bei und aktualisiert die Dreh-Metadaten, was schneller ist, aber davon abhängt, dass die nächste App das Flag korrekt liest.

### Verwenden Sie dies, wenn:

- **Ihr Handyclip seitlich ist**: Drehen Sie Hoch- oder Querformat-Aufnahmen hochkant, bevor Sie sie hochladen.
- **Ihr Video auf dem Kopf steht**: Drehen Sie um 180°, wenn die Kameraausrichtung während der Aufnahme falsch war.
- **Ihre App Dreh-Metadaten ignoriert**: Brennen Sie die Drehung in die Pixel ein, sodass die Ausgabe nicht von einem versteckten Flag abhängt.
- **Sie einen schnellen MP4-Export benötigen**: Speichern Sie ein korrigiertes MP4, ohne einen Desktop-Videoeditor zu öffnen.

Wenn Sie auf Instagram, TikTok, YouTube oder einer anderen Plattform posten, die die Datei möglicherweise erneut verarbeitet, wählen Sie **Social-ready** für das vorhersagbarste Ergebnis.

## Social-ready vs. Fast Remux

| Bedarf | Social-ready | Fast remux |
| --- | --- | --- |
| Was sich ändert | Dreht die tatsächlichen Videoframes und entfernt das Dreh-Flag | Behält die Originalframes bei und aktualisiert die MP4-Dreh-Metadaten |
| Geschwindigkeit | Langsamer, da das Video in H.264 neu codiert wird | Nahezu sofort, da die komprimierten Videopakete kopiert werden |
| Qualität | Hochwertiger H.264-Export, aber dennoch eine Neucodierung | Identisch zum Quellvideostream |
| Am besten für Social-Media-Uploads | Beste Wahl, wenn die nächste App Dreh-Metadaten ignorieren könnte | Funktioniert nur, wenn die nächste App das Dreh-Flag respektiert |
| Ausgabe | Hochkante Pixel in einer MP4-Datei | Gleiche Pixel mit korrigierter Drehanweisung |

Beide Modi laufen lokal in Ihrem Browser. Ihr Originalvideo wird nicht hochgeladen, und der Export hat kein Wasserzeichen.

## Wann Sie neu codieren statt remuxen sollten

Fast remux ist nützlich, wenn Sie eine schnelle lokale Korrektur wünschen und wissen, dass der nächste Player MP4-Dreh-Metadaten liest. Es kann die richtige Wahl für die Vorschau, Archivierung oder das Senden einer Datei an eine App sein, die Dreh-Flags korrekt verarbeitet.

Social-ready ist besser, wenn der Clip hochgeladen, erneut komprimiert oder auf verschiedenen Geräten geöffnet wird. Indem Sie hochkante Pixel in das MP4 schreiben, eliminieren Sie die Unsicherheit. Ihr Export dauert möglicherweise länger, aber die Datei wird von sozialen Plattformen und einfachen Playern korrekt angezeigt.

### Eine einfache Regel:

Wenn das Video zum Posten gedacht ist, wählen Sie **Social-ready**. Wenn das Video für Ihr eigenes Gerät ist und Sie die schnellstmögliche Korrektur wünschen, probieren Sie **Fast remux**.

## Video drehen auf einen Blick

### Advantages

- Private Verarbeitung ohne Server-Upload.
- Drehoptionen um 90°, 180° und 270°.
- Social-ready MP4-Export für vorhersagbare Ausrichtung.
- Fast remux Option, wenn nur eine Metadatenkorrektur nötig ist.
- Kostenloser Export ohne Wasserzeichen.

### Disadvantages

- Social-ready-Modus codiert das Video neu, daher dauert der Export länger als Remux.
- Fast remux hängt davon ab, dass die nächste App die Dreh-Metadaten respektiert.
- Nur rechtwinklige Drehungen werden unterstützt, keine beliebigen Winkel.
- Erfordert einen modernen Browser mit WebCodecs-Unterstützung.

> von manchen Playern beachtet, von anderen nicht
>
> Stack Overflow Diskussion über MP4-Dreh-Metadaten

## Video drehen - FAQ

### Kann ich ein Video drehen, ohne es hochzuladen?

Ja. GrepCut führt den Drehvorgang in Ihrem Browser durch, sodass Ihre Datei auf Ihrem Gerät bleibt und nicht auf einen Server hochgeladen wird.

### Warum sieht mein MP4 in einer App seitlich aus, in einer anderen aber korrekt?

Ihr MP4 enthält möglicherweise Dreh-Metadaten. Manche Player lesen diese Anweisung und drehen das Video während der Wiedergabe, während andere Apps sie ignorieren. Verwenden Sie den Modus **Social-ready**, wenn das exportierte MP4 hochkante Pixel enthalten soll, anstatt sich auf Metadaten zu verlassen.

### Sollte ich Social-ready oder Fast remux verwenden?

Verwenden Sie **Social-ready**, wenn Sie den Clip online posten oder an eine App senden möchten, die Dreh-Flags ignorieren könnte. Verwenden Sie **Fast remux**, wenn Sie den schnellsten Export wünschen und der nächste Player voraussichtlich MP4-Dreh-Metadaten respektiert.

### Verringert das Drehen meines Videos die Qualität?

Fast remux lässt den ursprünglichen Videostream unverändert, sodass der Videostream identisch bleibt. Social-ready codiert in H.264 neu, sodass die Drehung in die Pixel eingebrannt wird - zuverlässiger zum Posten, aber zeitaufwändiger.

### Welche Videoformate kann ich drehen?

Sie können MP4, MOV, WebM, MKV, M4V und die meisten gängigen Videoformate hinzufügen. GrepCut exportiert das gedrehte Ergebnis als MP4.

### Bleibt der Ton nach dem Drehen synchron?

Ja. Die Drehung ändert die Wiedergabegeschwindigkeit nicht. Der Ton wird verlustfrei kopiert, wenn er bereits AAC ist, oder zur breiten MP4-Kompatibilität in AAC neu codiert.

### Kann ich um einen benutzerdefinierten Winkel wie 12° drehen?

Nein. Dieses Tool ist für rechtwinklige Korrekturen ausgelegt: 90° im Uhrzeigersinn, 180° und 90° gegen den Uhrzeigersinn. Für seitliche Handyaufnahmen sind das in der Regel die benötigten Korrekturen.

### Warum benötigt GrepCut einen modernen Browser?

Der Social-ready-Export ist auf Browser-Videoverarbeitungsfunktionen wie WebCodecs angewiesen. Wenn Ihr Browser die erforderlichen APIs nicht unterstützt, versuchen Sie es mit einem aktuellen Chromium-basierten Browser.

## Quellen & weiterführende Links

- [Reddit-Diskussion über versehentliches Filmen im Hochformat](https://www.reddit.com/r/VideoEditing/comments/xryq3n/i_accidentally_filmed_my_videos_in_portrait_mode/)
- [Reddit-Frage zum Drehen ohne Neucodierung](https://www.reddit.com/r/VideoEditing/comments/uuw62f/automatically_rotate_video_without_actually/)
- [Super User Erklärung zu iPhone-Video-Dreh-Metadaten](https://superuser.com/questions/564233/iphone-recorded-videos-getting-rotated-on-windows-systems)
- [Stack Overflow Diskussion über MP4-Dreh-Flags](https://stackoverflow.com/questions/69386275/mp4-and-rotation-remove-flags-but-set-rotation)
- [MDN Leitfaden zur WebCodecs API](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [W3C WebCodecs Spezifikation](https://www.w3.org/TR/webcodecs/)

## Fertig mit Drehen? Erstellen Sie den vollständigen Schnitt

Öffnen Sie GrepCut Studio, um zuzuschneiden, die Größe zu ändern, Untertitel hinzuzufügen, Musik einzufügen und Ihre browserbasierte Videobearbeitung abzuschließen.

## Verwandte Tools

- [Video zuschneiden](https://grepcut.com/de/tools/crop-video) - Rahmen auf einen Bereich oder ein Seitenverhältnis zuschneiden.
- [Video skalieren](https://grepcut.com/de/tools/resize-video) - Clip prozentual skalieren.
- [Video trimmen](https://grepcut.com/de/tools/video-trimmer) - Clip vor oder nach dem Drehen kürzen.
