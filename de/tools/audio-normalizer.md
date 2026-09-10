# Online Audio-Lautheitsnormalisierer

Messen Sie die integrierte Lautheit und normalisieren Sie Ihre Tracks auf -14, -16 oder -23 LUFS. Läuft vollständig in Ihrem Browser, ohne Upload, ohne Konto.

HTML: https://grepcut.com/de/tools/audio-normalizer

## So normalisieren Sie die Lautstärke von Audio online

1. **Audio hochladen**: Ziehen Sie eine MP3-, WAV-, M4A- oder OGG-Datei in die Upload-Karte.
2. **LUFS-Ziel auswählen**: Wählen Sie Streaming bei -14 LUFS, Podcast bei -16 LUFS oder Broadcast bei -23 LUFS.
3. **Normalisieren und WAV exportieren**: Klicken Sie auf Normalisieren, um die Lautstärke zu messen, eine sichere Verstärkung mit Peak-Limiting anzuwenden und eine WAV-Kopie herunterzuladen.

Ihre Datei wird lokal in Ihrem Browser verarbeitet. Es wird nichts an GrepCut hochgeladen.

## Warum Ihr Audio LUFS braucht, nicht nur Peak-Normalisierung

Wenn Ihr Clip nahe 0 dB peakt, aber im Vergleich zu anderen Audiodateien leise klingt, löst die Peak-Normalisierung das eigentliche Problem nicht. Peaks zeigen nur das lauteste Sample, während LUFS abschätzt, wie laut Ihr Track über die Zeit wirkt.

GrepCut misst die integrierte Lautstärke mit K-Bewertung, wendet dann eine Verstärkung in Richtung des gewählten Ziels an und respektiert dabei eine Peak-Obergrenze von -1 dBTP. So landet Ihr Audio näher an einem Streaming-, Podcast- oder Broadcast-Lautstärkeziel, ohne dass Peaks ins Clipping geraten.

### Verwenden Sie dies, wenn Sie eine konsistente wahrgenommene Lautstärke wünschen, bevor Sie teilen, veröffentlichen oder weiter bearbeiten.

Wenn Ihre Datei bereits sehr laut ist und keinen Headroom mehr hat, kann die Peak-Obergrenze das Tool daran hindern, das exakte LUFS-Ziel zu erreichen. In diesem Fall ist das sicherere Ergebnis meist besser als ein verzerrtes Ergebnis.

## Welches LUFS-Ziel sollten Sie wählen?

| Ziel | Am besten geeignet für | Was es bewirkt |
| --- | --- | --- |
| -14 LUFS | Streaming-Videos oder Musikvorschauen | Ein gängiges Lautstärkeziel, wenn Ihr Audio näher an den Wiedergabepegeln großer Streaming-Dienste liegen soll. |
| -16 LUFS | Podcasts und Sprachclips | Ein praktisches Ziel für sprachlastige Inhalte, bei denen Klarheit und Konsistenz wichtiger sind als maximale Lautstärke. |
| -23 LUFS | Broadcast-ähnliche Auslieferung | Ein leiseres Ziel, das an EBU-R128-Broadcast-LautstärkeAbläufe angelehnt ist. |

Diese Voreinstellungen sind Ausgangspunkte. Ihre endgültige Veröffentlichungsplattform kann nach der Veröffentlichung eine eigene Wiedergabenormalisierung anwenden.

## Was in Ihrem Browser passiert

Wenn Sie eine Datei hinzufügen, dekodiert Ihr Browser das Audio, damit GrepCut die Wellenform analysieren kann. Das Tool misst die Lautstärke über den gesamten Track, berechnet die erforderliche Verstärkung für Ihr gewähltes LUFS-Ziel und begrenzt das Ergebnis, sodass die Peaks unter der Obergrenze bleiben.

Da die Verarbeitung lokal erfolgt, bleibt Ihr Audio auf Ihrem Gerät. Sehr lange Dateien können länger dauern, da Ihr Browser das Audio dekodieren und im Arbeitsspeicher verarbeiten muss.

- **Privat von Grund auf**: Ihr Quell-Audio wird nicht auf einen Server hochgeladen.
- **LUFS-bewusst**: Das Tool zielt auf die wahrgenommene Lautstärke ab, nicht nur auf den höchsten Sample-Peak.
- **WAV-Export**: Das normalisierte Ergebnis wird als WAV-Datei heruntergeladen - zur Bearbeitung, Archivierung oder Konvertierung.

## Wann Lautstärkenormalisierung am hilfreichsten ist

Verwenden Sie die LUFS-Normalisierung, wenn Ihre Sprachnotiz, Ihr Podcast-Segment, Ihre Bildschirmaufnahme oder Ihr Musikclip im Vergleich zum Rest Ihres Projekts viel leiser oder lauter klingt. Besonders nützlich ist sie, bevor Sie mehrere Clips in einer Timeline zusammenfügen.

Bei Sprache sollten Sie vor der Normalisierung möglicherweise Rauschen entfernen, entzerren, komprimieren oder Pausen bearbeiten. Die Lautstärkenormalisierung ist in der Regel der letzte Schritt zur Pegelangleichung und kein Ersatz für die Behebung einer verrauschten Aufnahme oder einer ungleichmäßigen Darbietung.

## Vorteile und Grenzen des Audio Normalizers

### Advantages

- Sie können MP3, WAV, M4A oder OGG normalisieren, ohne Ihre Datei hochzuladen.
- Sie können klare LUFS-Voreinstellungen für Streaming, Podcast oder Broadcast wählen.
- Peak-Limiting reduziert das Clipping-Risiko bei Verstärkung.

### Disadvantages

- Das Exportformat ist WAV, nicht MP3 oder M4A.
- Eine Datei ohne verbleibenden Headroom erreicht möglicherweise nicht das exakte LUFS-Ziel ohne Clipping.
- Die Browser-Dekodierungsunterstützung kann je nach Datei-Codec und Gerät variieren.

> Normalisierung passt jeden Song auf denselben Spitzenpegel an, aber das ist nicht dasselbe wie sie auf dieselbe Lautstärke anzupassen.
>
> Reddit r/audioengineering

## Häufig gestellte Fragen zum Audio Normalizer

### Kann ich Audio online auf -14 LUFS normalisieren?

Ja. Wählen Sie die Voreinstellung Streaming, um -14 LUFS anzusteuern, und exportieren Sie das normalisierte Ergebnis als WAV. Ihr Browser führt die Verarbeitung lokal durch, Ihre Datei wird nicht hochgeladen.

### Sollte ich -14 LUFS oder -16 LUFS verwenden?

Verwenden Sie -14 LUFS, wenn Sie ein gängiges Streaming-Ziel wünschen. Verwenden Sie -16 LUFS, wenn Sie Sprachaudio wie ein Podcast-Segment vorbereiten. Wenn Sie unsicher sind, wählen Sie die Voreinstellung, die zu Ihrem Verwendungszweck passt.

### Kann ich Audio für Broadcast-Lautstärke normalisieren?

Ja. Wählen Sie die Voreinstellung Broadcast, um -23 LUFS anzusteuern. Dies ist nützlich, wenn Sie ein leiseres Broadcast-ähnliches Lautstärkeziel anstelle eines Streaming- oder Podcast-Ziels wünschen.

### Wird meine Audiodatei hochgeladen?

Nein. GrepCut verarbeitet Ihr Audio in Ihrem Browser. Die Quelldatei bleibt auf Ihrem Gerät, und die normalisierte WAV wird lokal erzeugt.

### Verzerrt die Lautstärkenormalisierung mein Audio?

Das Tool wendet eine Verstärkung mit einer Peak-Obergrenze von -1 dBTP an, um das Clipping-Risiko zu reduzieren. Wenn Ihre Quelle bereits sehr laut ist, kann der Limiter das exakte LUFS-Ziel verhindern, damit der Export sicherer bleibt.

### Warum klingt meine Datei nach der LUFS-Anpassung immer noch anders?

LUFS ist ein guter Lautstärke-Anhaltspunkt, aber Klangfarbe, Bass, Kompression, Hintergrundgeräusche und Dynamikumfang beeinflussen weiterhin, wie laut Ihr Audio wirkt. Zwei Dateien können denselben LUFS-Wert haben und sich dennoch unterschiedlich anfühlen.

### Kann ich nach der Normalisierung MP3 exportieren?

Dieses Tool exportiert WAV. Wenn Sie ein anderes Ausgabeformat benötigen, normalisieren Sie zuerst und konvertieren Sie dann die WAV mit einem separaten Konverter.

## Quellen & weiterführende Links

- [Reddit-Diskussion zur Podcast-Lautstärkenormalisierung](https://www.reddit.com/r/podcasts/comments/f1fbew/editing_question_do_you_normalize_and_if_so_how/)
- [Reddit-Diskussion zu Peak-Normalisierung vs. wahrgenommener Lautstärke](https://www.reddit.com/r/audioengineering/comments/kctip9/normalising_the_volume_of_100_tracks_at_once/)
- [Spotify-Leitfaden zur Lautstärkenormalisierung](https://support.spotify.com/us/artists/article/loudness-normalization/)
- [ITU-R BS.1770-5 Empfehlung zu Lautstärke und True-Peak](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1770-5-202311-I!!PDF-E.pdf)
- [MDN Web Audio API Übersicht](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [MDN decodeAudioData Referenz zur Browser-Audio-Dekodierung](https://developer.mozilla.org/en-US/docs/Web/API/BaseAudioContext/decodeAudioData)

## Normalisieren Sie Ihr Audio privat

Öffnen Sie den Audio Normalizer, wählen Sie Ihr LUFS-Ziel und exportieren Sie eine saubere WAV, ohne Ihre Datei an einen Server zu senden.

## Verwandte Tools

- [Audio-Rauschunterdrücker](https://grepcut.com/de/tools/audio-noise-remover) - Entferne Hintergrundgeräusche vor der Lautheitsnormalisierung.
- [Klingelton-Ersteller](https://grepcut.com/de/tools/ringtone-maker) - Schneide einen kurzen Clip und exportiere einen M4R- oder MP3-Klingelton.
