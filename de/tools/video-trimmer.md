# Kostenloser Online-Video-Trimmer

Schneiden Sie ein Video in unter 2 Sekunden auf den benötigten Teil zu. Mittels verlustfreiem, keyframe-basiertem Stream-Kopieren geschieht alles lokal in Ihrem Browser ohne Upload und ohne Qualitätsverlust.

HTML: https://grepcut.com/de/tools/video-trimmer

## So schneiden Sie ein Video in Ihrem Browser

1. **Video hinzufügen**: Ziehen Sie Ihre Datei auf den Trimmer oder klicken Sie zum Durchsuchen. Ihr Video wird lokal in der Vorschau geladen.
2. **Gewünschten Bereich auswählen**: Ziehen Sie die Anfangs- und Endmarkierungen und sehen Sie sich den Bereich vor dem Export in der Vorschau an.
3. **Schnitt exportieren**: Erstellen Sie ein getrimmtes MP4 mit keyframe-basiertem Stream-Kopieren oder setzen Sie die Bearbeitung in GrepCut Studio fort.

Benötigen Sie mehrere Schnitte, Untertitel, Musik oder das Entfernen eines Mittelteils? Öffnen Sie den Clip im [GrepCut Studio](/).

## Warum Ihr Video so schnell exportiert wird

Wenn Sie nur den Anfang oder das Ende eines Clips kürzen müssen, fühlt sich das Hochladen der gesamten Datei auf einen Server verschwenderisch an. GrepCut behält Ihre Datei auf Ihrem Gerät und schneidet sie direkt in Ihrem Browser.

Der Trimmer verwendet WebCodecs und MediaBunny, um die Mediendatei zu lesen, die bereits codierten Video- und Audio-Pakete zu kopieren und in ein neues MP4 zu remuxen. Da Ihr Browser nicht jedes Bild decodieren und neu codieren muss, ist der Export meist in Sekunden abgeschlossen.

### Sie erhalten einen schnellen Schnitt, weil GrepCut den langsamsten Teil der Bearbeitung vermeidet:

- **Keine vollständige Transcodierung**: Der ausgewählte Bereich wird aus dem Quellstream kopiert, anstatt von Grund auf neu codiert zu werden.
- **Keine Wartezeit für den Upload**: Ihre Datei bleibt lokal, sodass Sie nicht auf einen Server-Upload warten müssen, bevor der Schnitt beginnt.
- **Kein Qualitätsverlust durch Generationsverlust**: Der Stream-Kopierpfad bewahrt die ursprüngliche codierte Medienqualität im exportierten Bereich.

## Was keyframe-basiertes Schneiden für Sie bedeutet

Ein komprimiertes Video ist nicht nur ein Stapel vollständiger Bilder. Die meisten Frames hängen von benachbarten Frames ab, und Keyframes sind die sicheren Punkte, an denen die Wiedergabe sauber starten kann.

Deshalb kann ein verlustfreier Stream-Copy-Trimmer Ihren Schnitt auf den nächstgelegenen verwendbaren Keyframe setzen, anstatt auf einem beliebigen Frame zu schneiden. Sie erhalten ein schnelles, standardkonformes MP4, aber der exportierte Start oder das Ende kann etwas früher oder später als die Markierungsposition liegen.

Wenn Sie einen frame-genauen Schnitt, visuelle Effekte, Übergänge oder einen Schnitt in der Mitte eines Clips benötigen, verwenden Sie den vollständigen Editor anstelle des Ein-Bereich-Trimmers.

## Browser-Trimmer vs. traditioneller Online-Trimmer

| Was Sie brauchen | GrepCut Video-Trimmer | Typischer Server-Trimmer |
| --- | --- | --- |
| Privatsphäre | Ihr Video bleibt auf Ihrem Gerät | Ihr Video wird vor der Verarbeitung hochgeladen |
| Geschwindigkeit | Schnelles Stream-Kopieren für einen durchgehenden Bereich | Upload plus Server-Verarbeitungszeit |
| Qualität | Behält die Quellqualität für den kopierten Bereich bei | Kann neu codieren und Generationsverlust verursachen |
| Schnittgenauigkeit | An sichere Video-Keyframes angepasst | Kann frame-genau sein, wenn der Server neu codiert |
| Beste Verwendung | Schnelles Entfernen von Anfang oder Ende eines Clips | Schwerere Bearbeitungen, Formatänderungen oder frame-genaue Exporte |

Wählen Sie GrepCut für einen privaten, schnellen, upload-freien Schnitt. Wählen Sie einen vollständigen Editor, wenn Ihre Bearbeitung frame-genaues Timing oder mehrere separate Bereiche erfordert.

## Bevor Sie schneiden

### Advantages

- Ihre Datei wird nicht auf einen Server hochgeladen.
- Die Vorschau aktualisiert sich während der Bereichsanpassung.
- Stream-Kopieren behält die Quellqualität des ausgewählten Bereichs bei.
- Kein Wasserzeichen, kein Konto und keine Installation.

### Disadvantages

- Schnittpunkte werden an nahegelegene Keyframes angepasst.
- Sehr große Dateien hängen vom Gerätespeicher ab.
- Dieses Tool behält nur einen durchgehenden Bereich bei.
- Sie benötigen einen Browser mit WebCodecs-Unterstützung.

> Sie können ein Video nur an einem Keyframe schneiden (ohne Codierung)
>
> Reddit r/ffmpeg Diskussion

## Video-Trimmer FAQ

### Wird Ihr Video beim Trimmen hochgeladen?

Nein. Ihre Datei wird lokal in Ihrem Browser verarbeitet, sodass sie Ihr Gerät nicht verlässt.

### Verschlechtert das Trimmen Ihre Videoqualität?

Auf dem Stream-Copy-Pfad tritt kein Qualitätsverlust auf. GrepCut kopiert die codierten Medien aus Ihrem ausgewählten Bereich und remuxt sie in ein neues MP4.

### Warum ist Ihr Schnitt nicht frame-genau?

Verlustfreies Video-Trimming muss Keyframes respektieren. Wenn Ihre gewählte Start- oder Endzeit zwischen Keyframes liegt, passt GrepCut den Schnitt an einen nahegelegenen sicheren Punkt an, damit das exportierte MP4 korrekt abgespielt wird.

### Können Sie die Mitte eines Videos herausschneiden?

Dieser Trimmer behält einen durchgehenden Bereich bei. Wenn Sie einen Mittelteil entfernen oder mehrere Schnitte machen müssen, öffnen Sie den Clip im [GrepCut Studio](/).

### Können Sie eine große Videodatei trimmen?

Ja, aber Ihr Browser und Gerätespeicher spielen eine Rolle. Da die Datei lokal verarbeitet wird, können sehr große Videos eher durch Ihren Computer als durch ein Upload-Limit begrenzt sein.

### Welche Browser funktionieren am besten?

Verwenden Sie einen Browser mit WebCodecs-Unterstützung, wie Chrome, Edge oder Opera. Wenn Ihr Browser die erforderlichen Medien-APIs nicht unterstützt, läuft der Trimmer möglicherweise nicht.

### Welche Datei erhalten Sie nach dem Trimmen?

Sie exportieren ein MP4 mit dem ausgewählten durchgehenden Bereich. Ziel ist eine weitgehend abspielbare Datei, ohne Ihr gesamtes Video hochzuladen oder zu transcodieren.

## Quellen & weiterführende Lektüre

- [Reddit-Diskussion zum Schneiden von Videos ohne Neucodierung an Keyframes](https://www.reddit.com/r/ffmpeg/comments/10tj7nu/can_you_only_cut_videos_without_reencoding_on/)
- [Reddit-Diskussion zum Trimmen von Videos ohne Neucodierung](https://www.reddit.com/r/ffmpeg/comments/1qag2ug/trimming_video_without_reencoding/)
- [Super User-Diskussion zum Schneiden von Videos ohne oder mit minimaler Neucodierung](https://superuser.com/questions/1850814/how-to-cut-a-video-with-ffmpeg-with-no-or-minimal-re-encoding)
- [Super User-Diskussion zum schnellen Videoschneiden und Stream-Kopieren](https://superuser.com/questions/1643484/fast-and-relatively-accurate-cutting-from-a-video)
- [MDN WebCodecs API-Übersicht](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [MediaBunny Browser-Medien-Toolkit](https://mediabunny.dev/)

## Schneiden Sie Ihren Clip und bearbeiten Sie weiter

Nutzen Sie den Trimmer für einen privaten, schnellen Schnitt. Wenn Ihr Clip Untertitel, Musik, Layout-Änderungen oder eine vollständige Timeline benötigt, öffnen Sie ihn in GrepCut Studio und bauen Sie im Browser weiter.

## Verwandte Tools

- [Video zuschneiden](https://grepcut.com/de/tools/crop-video) - Rahmen Sie Ihren Clip auf einen Bereich oder ein Seitenverhältnis zu.
- [Video skalieren](https://grepcut.com/de/tools/resize-video) - Skalieren Sie getrimmte Clips auf eine neue Auflösung oder ein neues Seitenverhältnis.
- [Video stummschalten](https://grepcut.com/de/tools/mute-video) - Entfernen Sie die Audiospur aus Ihrem Clip.
