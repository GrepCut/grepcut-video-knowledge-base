# Audio zu Video online hinzufügen

Video- und Audiodatei ablegen - GrepCut ersetzt die Tonspur, ohne das Bild neu zu kodieren. Nichts verlässt Ihr Gerät.

HTML: https://grepcut.com/de/tools/add-audio-to-video

## So fügen Sie Audio zu einem Video im Browser hinzu

1. **Wählen Sie Ihr Video**: Ziehen Sie eine MP4-, MOV-, WebM-, MKV-, M4V-, AVI-, OGV-, 3GP- oder MPEG-Datei in GrepCut. Ihr Video bleibt auf Ihrem Gerät.
2. **Wählen Sie Ihr Audio**: Fügen Sie eine MP3-, WAV-, AAC-, M4A-, FLAC-, OGG- oder Opus-Datei hinzu. Diese Datei wird zum Ersatz-Soundtrack.
3. **Mischen und exportieren**: Klicken Sie auf „Mischen und exportieren“. GrepCut verbindet den Videostream und Ihr neues Audio zu einer MP4-Datei.
4. **Ergebnis herunterladen**: Speichern Sie die MP4 mit dem Zusatz -with-audio im Dateinamen. Der Export endet mit der kürzeren der beiden Eingabedateien.

Möchten Sie Hintergrundmusik mit der Originalstimme mischen, Lautstärke anpassen, Audio ein- oder ausblenden oder eine Spur um einige Frames synchronisieren? Öffnen Sie stattdessen [GrepCut Studio](/).

## Was dieser Audiotausch tatsächlich ändert

Wenn Sie bereits ein fertiges Video und eine separate Sprachaufnahme, einen Song, eine Erzählung oder eine bereinigte Audiodatei haben, benötigen Sie keinen vollständigen Editor, nur um den Soundtrack zu ersetzen. GrepCut nimmt den Videostream aus Ihrer ersten Datei und den Audiostream aus Ihrer zweiten Datei und schreibt sie in eine MP4.

Ihr ursprünglicher Soundtrack wird nicht beibehalten. Die neue Audiodatei wird zur einzigen Audiospur im Export. Dies ist nützlich, wenn Ihr Clip stumm, verrauscht, von einer Plattform stummgeschaltet oder mit der falschen Audioaufnahme exportiert wurde.

Der Videostream wird nach Möglichkeit kopiert, sodass das Bild nicht neu komprimiert wird, nur weil Sie das Audio geändert haben. Wenn der Videocodec nicht sauber in MP4 kopiert werden kann, benötigen Sie möglicherweise einen anderen Ablauf im vollständigen Editor.

Die Kernidee ist einfach: Sie ersetzen eine Spur, nicht die gesamte Bearbeitung.

## Audio-Ersatz vs. Vollständige Bearbeitung

| Was Sie brauchen | Dieses Schnelltool verwenden | GrepCut Studio verwenden |
| --- | --- | --- |
| Schlechtes Kamera-Audio durch separate MP3 oder WAV ersetzen | Ja, das ist der HauptAblauf | Nur wenn Sie auch Bearbeitungen benötigen |
| Sprachaufnahme zu einer stummen Bildschirmaufnahme hinzufügen | Ja, wenn eine Audiodatei ausreicht | Für Timing-Anpassungen verwenden |
| Original-Audio behalten und Musik darüber legen | Nein, das Original-Audio wird ersetzt | Ja, mehrere Spuren verwenden |
| Musik ein- oder ausblenden | Nein, nur schneller Ersatz | Ja, Lautstärkeregelung verwenden |
| Audio korrigieren, das zu spät oder zu früh beginnt | Keine präzisen Synchronisationssteuerungen hier | Ja, auf der Timeline ausrichten |

Verwenden Sie das Schnelltool, wenn Ihr Video und das Ersatz-Audio bereits gut zusammenpassen. Verwenden Sie das Studio, wenn Ihr Audio Bearbeitung, Mischung oder Timing-Arbeit benötigt.

## Unterstützte Video- und Audioeingaben

Beginnen Sie mit einer Videodatei. GrepCut ist für MP4-, MOV-, WebM-, MKV-, M4V-, AVI-, OGV-, 3GP- und MPEG-Eingaben ausgelegt, sowie für andere lesbare Videodateien, wenn der Browser und FFmpeg sie parsen können.

Fügen Sie dann eine Audiodatei hinzu. MP3, WAV, AAC, M4A, FLAC, OGG und Opus sind die getesteten Audioeingaben. Die Ausgabe ist immer eine MP4, was das Ergebnis einfacher zu teilen, abzuspielen und in gängige Apps zu importieren macht.

### Einige praktische Format-Hinweise:

- **MP4 und MOV**: gut für Handy-Clips, Bildschirmaufnahmen, Kameraexporte und Entwürfe für soziale Medien.
- **WebM und MKV**: nützlich, wenn Ihre Quelle von einem Browser-Recorder, Download oder Open-Source-Ablauf stammt.
- **WAV und FLAC**: gut für saubere Sprachaufnahmen oder Musik-Master vor der Erstellung der finalen MP4.
- **OGG und Opus**: nützlich für Audio, das von Web-Apps, Spielen oder offenen Medien-Tools aufgenommen wurde.

Wenn eine Datei geöffnet wird, der Export jedoch fehlschlägt, liegt der übliche Grund nicht in der Dateierweiterung, sondern im Codec innerhalb des Containers.

## Warum Ihr Export bei der kürzeren Datei endet

GrepCut kürzt den Export auf die kürzere Eingabe, damit Sie keinen langen schwarzen Nachlauf, ein stummes Ende oder verstecktes zusätzliches Audio nach dem Ende des Bildes erhalten. Wenn Ihr Song länger als der Clip ist, wird der Song am Ende des Videos abgeschnitten. Wenn Ihre Sprachaufnahme kürzer als der Clip ist, endet das exportierte Video, wenn die Sprachaufnahme endet.

Dieses Verhalten ist für ein schnelles Ersatz-Tool beabsichtigt. Es hält das Ergebnis vorhersagbar, ohne Schleifen, Auffüllen, Einblendungen oder Stummschaltung zu erzeugen. Für diese Timing-Entscheidungen verwenden Sie die vollständige Timeline in GrepCut Studio.

## Was Sie mit einem browserbasierten Audiotausch erhalten

### Advantages

- Ihr Video und Audio bleiben auf Ihrem Gerät, kein Upload.
- Das Bild wird nicht neu codiert, wenn Stream-Kopie möglich ist.
- Sie erhalten eine MP4, die einfacher abzuspielen und zu teilen ist.
- Sie können verrauschtes, stummgeschaltetes oder falsches Audio ersetzen, ohne eine vollständige Timeline zu öffnen.
- Sie können gängige Videoeingaben und Audioformate verwenden.

### Disadvantages

- Es wird nur eine Ersatz-Audiodatei verwendet.
- Das Original-Audio wird entfernt, nicht darunter gemischt.
- Lautstärkeänderungen, Einblendungen, Ducking und exakte Synchronisation erfordern GrepCut Studio.
- Sehr große Dateien hängen von Ihrem Gerätespeicher und Browserlimits ab.
- Einige ungewöhnliche Codecs müssen möglicherweise konvertiert werden, bevor sie in MP4 passen.

> Das Rendern macht das Video entweder dreimal so groß oder es gibt einen erheblichen Qualitätsverlust bei gleicher Dateigröße
>
> Reddit r/davinciresolve

## Häufig gestellte Fragen zum Hinzufügen von Audio zu Video

### Kann ich Audio in einer MP4 ersetzen, ohne das Video erneut zu rendern?

Ja, wenn der Videostream in die Ausgabe-MP4 kopiert werden kann. GrepCut versucht, den Bildstream zu kopieren, anstatt ihn neu zu codieren, sodass das Ändern des Soundtracks nicht automatisch einen Qualitätsverlust bedeutet.

### Werden mein Video oder Audio hochgeladen?

Nein. GrepCut führt den Audiotausch lokal in Ihrem Browser mit FFmpeg, kompiliert zu WebAssembly, durch. Ihre Dateien bleiben auf Ihrem Gerät.

### Kann ich den Originalton behalten und Musik darüber legen?

Nicht in diesem Schnelltool. Das Ersatz-Audio wird zum einzigen Soundtrack. Verwenden Sie [GrepCut Studio](/), wenn Sie Musik, Dialoge und Soundeffekte zusammen abspielen möchten.

### Was passiert, wenn mein Audio länger als mein Video ist?

Der Export endet am Ende der kürzeren Datei. Wenn Ihr Audio länger als das Video läuft, wird es abgeschnitten. Wenn Ihr Audio kürzer ist, endet das Video damit.

### Kann ich Audio synchronisieren, das zu früh oder zu spät beginnt?

Dieses Tool enthält keine Offset-Steuerungen. Wenn Ihre Sprachaufnahme eine frame-genaue Ausrichtung benötigt, öffnen Sie das Video in [GrepCut Studio](/) und verschieben Sie das Audio auf der Timeline.

### Welche Formate kann ich mit Audio versehen?

Sie können mit MP4-, MOV-, WebM-, MKV-, M4V-, AVI-, OGV-, 3GP- oder MPEG-Video beginnen. Ihr Ersatz-Audio kann MP3, WAV, AAC, M4A, FLAC, OGG oder Opus sein. Die heruntergeladene Datei ist MP4.

### Warum exportiert GrepCut MP4 anstatt den ursprünglichen Container beizubehalten?

MP4 wird von Browsern, Telefonen, Editoren und Social-Apps weitgehend unterstützt. Die Beibehaltung eines Ausgabecontainers macht das Schnelltool auch einfacher und vorhersagbarer.

### Verliert meine Datei an Qualität?

Das Bild sollte gleich bleiben, wenn die Stream-Kopie funktioniert. Das Audio wird aus Ihrer Ersatzdatei übernommen und in die Ausgabe gemultiplext, daher hängt das Ergebnis von der Qualität der von Ihnen bereitgestellten Audiodatei ab.

## Quellen & weiterführende Lektüre

- [Reddit-Diskussion zum Ersetzen von MP4-Audio ohne Rendern](https://www.reddit.com/r/davinciresolve/comments/1fnsfjb/how_do_i_replace_the_audio_of_an_mp4_without/)
- [Super User-Thread zum Ersetzen von Audio in Video mit FFmpeg](https://superuser.com/questions/1137612/ffmpeg-replace-audio-in-video)
- [Super User-Thread zum Verhalten von Audio- und Videolänge](https://superuser.com/questions/801547/ffmpeg-add-audio-but-keep-video-length-the-same-not-shortest)
- [Reddit-Diskussion zum Bearbeiten von Audio ohne Video-Neucodierung](https://www.reddit.com/r/VideoEditing/comments/v1n6tu/edit_audio_without_reencoding_video/)
- [FFmpeg-Dokumentation zu Stream-Spezifizierern und Codec-Kopie](https://ffmpeg.org/ffmpeg.html)
- [MDN-Leitfaden zu Mediencontainerformaten](https://developer.mozilla.org/de/docs/Web/Media/Guides/Formats/Containers)

## Ersetzen Sie Ihren Video-Soundtrack privat

Öffnen Sie GrepCut, fügen Sie Ihr Video hinzu, fügen Sie Ihr Ersatz-Audio hinzu und exportieren Sie eine MP4, ohne Ihre Dateien hochzuladen.

## Verwandte Tools

- [Video stummschalten](https://grepcut.com/de/tools/mute-video) - entferne die Tonspur, bevor du eine neue hinzufügst.
- [Video zuschneiden](https://grepcut.com/de/tools/video-trimmer) - schneide deinen Clip, bevor du den Ton ersetzt.
- [SRT-Untertitel einbrennen](https://grepcut.com/de/tools/burn-srt-subtitles-to-video) - brenne Untertitel ein, nachdem die Tonspur ersetzt wurde.
