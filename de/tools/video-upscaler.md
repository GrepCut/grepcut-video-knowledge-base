# Kostenloser Online FSR Video-Upscaler

Erhöhen Sie die Clip-Auflösung mit kantengerechtem FSR-Upscaling in Ihrem Browser.

HTML: https://grepcut.com/de/tools/video-upscaler

## Lesen Sie dies zuerst: FSR schärft Kanten, es erfindet keine Details

Setzen Sie Ihre Erwartungen, bevor Sie beginnen. FSR macht Kanten sauberer, während es Ihren Clip vergrößert, aber bei bereits weichem, niedrig-bitratigem oder unscharfem Material ist die Verbesserung oft marginal, weil nur sehr wenige echte Kanteninformationen zum Rekonstruieren vorhanden sind.

FSR ist ein räumlicher Hochskalierer, keine KI. Es kann keine Details hinzufügen, die nie aufgezeichnet wurden. Das Wiederherstellen von Texturen, die nicht in Ihrer Quelle vorhanden sind, erfordert ein KI-Super-Resolution-Modell, ein anderes Werkzeug. Verwenden Sie diesen Hochskalierer, um sauber zu vergrößern und Kanten zu schärfen, nicht um verlorene Details wiederherzustellen.

## So skalieren Sie Videos online in Ihrem Browser hoch

1. **Laden Sie Ihren Clip hoch**: Legen Sie eine MP4-, MOV-, WebM- oder MKV-Datei auf den Upload-Bereich.
2. **Wählen Sie 2×, 3× oder 4×**: Wählen Sie den Hochskalierungsfaktor, der zu Ihrer Timeline, Ihrem Social-Export oder HD-Layout passt.
3. **Exportieren Sie Ihr MP4**: Laden Sie das hochskalierte MP4 herunter oder öffnen Sie es in GrepCut Studio für Untertitel, Schnitte und Feinschliff.

Die Hochskalierung erfolgt lokal in Ihrem Browser, sodass Ihr Video auf Ihrem Gerät bleibt.

## Verwenden Sie FSR-Hochskalierung, wenn Ihr Clip zu klein ist

Wenn Ihr Clip in 480p, 720p oder in einem kleinen Bildschirmaufnahmefenster aufgenommen wurde, kann er in einem HD-Schnitt unterdimensioniert wirken. Hochskalierung erhöht die Pixelabmessungen vor dem Export, sodass Ihr Video in eine 1080p-Timeline, einen YouTube-Upload oder ein Social-Preset passt, ohne manuelles Strecken in einem anderen Editor.

GrepCut skaliert mit FSR (AMD FidelityFX Super Resolution) hoch. Anstatt einer einfachen glatten Streckung rekonstruiert FSR Kanten beim Vergrößern, sodass Linien und Konturen schärfer bleiben als bei bikubischer Skalierung. Das macht es zu einer praktischen Wahl für komprimierte Handyaufnahmen, Tutorial-Clips und Reposts, die zu klein exportiert wurden.

### Am besten geeignet für:

- **Alte Handyaufnahmen**: Bringen Sie einen 480p- oder 720p-Clip mit saubereren Kanten näher an ein HD-Layout, bevor Sie ihn posten.
- **Bildschirmaufnahmen**: Machen Sie ein kleines Aufnahmefenster leichter in einem Tutorial- oder Präsentationsschnitt platzierbar.
- **Social-Reposts**: Ändern Sie die Größe von vertikalen Clips, die aus einer anderen App mit niedrigerer Auflösung zurückkamen.

## Wie FSR-Hochskalierung funktioniert und was sie reparieren kann und was nicht

FSR ist ein räumlicher Hochskalierer: Es arbeitet mit dem einzelnen Frame vor sich, ohne Bewegungsvektoren, Tiefenpuffer oder KI-Modell. Es läuft in zwei GPU-Durchläufen. Zuerst tastet EASU (Edge-Adaptive Spatial Upsampling) das Frame richtungsabhängig neu ab, erkennt, wie benachbarte Gradienten sich unterscheiden, sodass Kanten rekonstruiert statt nur unscharf gemacht werden. Dann fügt RCAS (Robust Contrast-Adaptive Sharpening) eine kontrollierte Schärfung hinzu, die Details hervorhebt, ohne Halos zu erzeugen oder Rauschen zu verstärken.

Da FSR gewöhnliche Shader verwendet und nie auf andere Frames schaut, behandelt es jeden Frame gleich und hält Ihren Export konsistent. Es ist jedoch keine KI-Super-Resolution. Wenn Ihre Quelle stark unscharf, stark komprimiert oder ohne feine Details ist, kann FSR einen größeren Frame mit schärferen Kanten erzeugen, aber es kann keine Textur wiederherstellen, die nie aufgezeichnet wurde.

### Unter der Haube:

- **EASU**: Kantenerhaltende Neuabtastung, die Kanten beim Vergrößern rekonstruiert, schärfer als bilinear oder bikubisch.
- **RCAS**: Kontrastadaptive Schärfung, automatisch angewendet, die echte Kanten betont und flache Bereiche in Ruhe lässt.

Bei sehr weichem Material testen Sie zuerst einen kurzen Export. Wenn die Vorschau bereits zu weich aussieht, wirkt ein kleinerer Faktor oft natürlicher als eine harte 4×-Streckung.

## Wie FSR im Vergleich zu einfacher Skalierung abschneidet

| Methode | Wie skaliert wird | Typisches Ergebnis |
| --- | --- | --- |
| Nächster Nachbar | Dupliziert den nächstgelegenen Pixel. | Blockig, harte treppenartige Kanten. |
| Bilinear oder bikubisch | Mittelt die umgebenden Pixel. | Glatter, aber Kanten wirken weich. |
| FSR (EASU + RCAS) | Kantenerhaltende Neuabtastung plus kontrastadaptive Schärfung. | Sauberere, schärfere Kanten ohne KI-Modell. |

FSR rekonstruiert Kanten, anstatt sie nur zu glätten, aber wie jede räumliche Methode arbeitet es mit den bereits im Clip vorhandenen Details.

## Welchen Hochskalierungsfaktor sollten Sie wählen?

Der richtige Faktor hängt davon ab, wie weit Ihr Clip von der benötigten Größe entfernt ist. Größere Faktoren erzeugen mehr Pixel zur Rekonstruktion, daher zeigt eine weiche Quelle ihre Grenzen bei 4× schneller als bei 2×.

### Wählen Sie Ihren Faktor:

- **2×**: Ein sicherer erster Test, wenn Ihr Clip nur eine moderate Größensteigerung benötigt.
- **3×**: Nützlich, wenn ein kleiner Clip mehr von einer HD-Leinwand ausfüllen muss.
- **4×**: Am besten für kurze Clips, bei denen Sie maximale Abmessungen benötigen und etwas länger warten können.

Beginnen Sie mit 2×, wenn Sie unsicher sind, und versuchen Sie es dann mit einem größeren Faktor, wenn Ihre Quelle genügend Details hat, um standzuhalten.

## Die Vorschau entspricht Ihrem Export

FSR skaliert und schärft automatisch hoch, daher gibt es nichts zu konfigurieren. Wählen Sie einen Faktor, überprüfen Sie das Ergebnis und exportieren Sie. EASU übernimmt die kantenerhaltende Vergrößerung und RCAS fügt eine feste, geschmackvolle Schärfung hinzu.

Die Vorher-Nachher-Vorschau verwendet dieselbe FSR-Pipeline wie der Export, sodass das, was Sie sehen, auch in Ihrem MP4 landet. Zoomen Sie die Vorschau hinein, um die Kantenschärfe zu beurteilen, bevor Sie sich für einen vollständigen Render entscheiden.

Wenn die Vorschau nach der Hochskalierung immer noch weich aussieht, bedeutet das normalerweise, dass das Detail nicht in der Quelle vorhanden war, und ein niedrigerer Faktor wirkt möglicherweise natürlicher.

## Halten Sie Ihr Video während des Tests privat

Online-Videotools verlangen oft, dass Sie die gesamte Datei hochladen, bevor Sie ein Ergebnis sehen können. Dieser Hochskalierer läuft stattdessen in Ihrem Browser, sodass Ihr Filmmaterial während der Verarbeitung Ihr Gerät nicht verlässt.

Das ist nützlich, wenn Ihr Clip private Bildschirminhalte, unveröffentlichtes Social-Material, Kundenentwürfe oder Unterrichtsaufnahmen enthält. Sie können einen Faktor testen, das MP4 herunterladen und die Bearbeitung fortsetzen, ohne die Originaldatei an einen Server zu senden.

Längere Clips und 4×-Exporte hängen von der Geschwindigkeit Ihres Geräts ab. Für schnelle Überprüfungen schneiden Sie den Clip zuerst zu oder testen Sie einen kurzen Abschnitt, bevor Sie das gesamte Video verarbeiten.

## Video Upscaler auf einen Blick

### Advantages

- Läuft lokal in Ihrem Browser ohne Hochladen.
- FSR rekonstruiert Kanten, daher sind Ergebnisse schärfer als bikubische Skalierung.
- EASU-Hochskalierung und RCAS-Schärfung werden automatisch angewendet, nichts zu konfigurieren.
- 2×-, 3×- und 4×-Voreinstellungen halten die Auswahl einfach.
- Kostenloser MP4-Export ohne Wasserzeichen.

### Disadvantages

- Es ist ein räumlicher Hochskalierer, keine KI, daher kann es keine nicht aufgezeichneten Details erfinden.
- Sehr unscharfe oder stark komprimierte Quellen können immer noch weich aussehen.
- Lange 4×-Exporte können auf langsameren Geräten länger dauern.
- Wenn Ihrem Browser WebGL2 fehlt, fällt er auf eine einfache bikubische Skalierung zurück.

> FSR 1 schaut sich keine vorherigen Frame-Daten an, um seine Hochskalierung zu verbessern, sondern streckt jedes isolierte Bild, wobei Techniken wie Kantenerkennung verwendet werden, um zu bestimmen, wie das Bild am besten gestreckt wird.
>
> PCGamesN

## FAQ zum Video-Upscaler

### Kann ich Video online hochskalieren, ohne es hochzuladen?

Ja. Ihr Video wird lokal in Ihrem Browser verarbeitet, sodass die Datei auf Ihrem Gerät bleibt.

### Ist FSR dasselbe wie KI-Hochskalierung?

Nein. FSR ist ein räumlicher Hochskalierer, der auf gewöhnlichen Shadern läuft und von einem einzelnen Frame ausgeht. Es rekonstruiert Kanten mit EASU und schärft mit RCAS, verwendet aber kein neuronales Netzwerk, daher kann es keine Details erfinden, wie es KI-Super-Resolution versucht.

### Wie unterscheidet sich FSR von bikubischer Hochskalierung?

Bikubisch mittelt benachbarte Pixel, was den Frame vergrößert, aber Kanten weich lässt. FSR untersucht, wie benachbarte Gradienten sich ändern, und tastet entlang von Kanten neu ab, sodass Linien und Konturen schärfer bleiben, dann fügt RCAS eine kontrollierte Schärfung hinzu.

### Macht FSR mein unscharfes Video scharf?

Es kann Kanten sauberer machen und etwas Biss hinzufügen, aber die Verbesserung ist bei weichem Material oft marginal, und es kann fehlende Details aus einer unscharfen, niedrig-bitratigen oder unscharfen Quelle nicht wiederherstellen. Das Wiederherstellen nicht vorhandener Details erfordert einen KI-Hochskalierer.

### Welchen Hochskalierungsfaktor sollte ich verwenden?

Verwenden Sie 2× für einen sicheren ersten Durchlauf, 3×, wenn Ihr Clip eine stärkere Größensteigerung benötigt, und 4× für kurze niedrigauflösende Clips, bei denen Sie die größte Ausgabe benötigen.

### Kann ich ein 480p-Video für einen 1080p-Schnitt hochskalieren?

Ja. Sie können den Clip vergrößern, bevor Sie ihn in eine HD-Timeline einfügen. FSR hält Kanten sauberer als eine einfache Streckung, obwohl das Ergebnis immer noch weicher aussehen kann als natives 1080p-Material, da das Original weniger Pixel hat.

### Muss ich Einstellungen anpassen?

Nein. FSR skaliert mit EASU hoch und schärft mit RCAS automatisch, Sie wählen einfach einen Faktor und exportieren. Die Vorher-Nachher-Vorschau verwendet dieselbe Pipeline wie der Export.

### Welche Videoformate kann ich importieren, und gibt es ein Wasserzeichen?

Sie können MP4-, MOV-, WebM- und MKV-Dateien importieren und Ihr hochskaliertes MP4 ohne Wasserzeichen exportieren.

## Quellen & weiterführende Literatur

- [AMD GPUOpen Übersicht über FidelityFX Super Resolution 1 (EASU und RCAS)](https://gpuopen.com/fidelityfx-superresolution/)
- [AMD GPUOpen FSR 1 räumliches Hochskalierungs-Technikhdbuch](https://gpuopen.com/manuals/fidelityfx_sdk/techniques/super-resolution-spatial/)
- [FidelityFX Super Resolution 1.0 entmystifiziert (Shader-Durchlauf)](https://jntesteves.github.io/shadesofnoice/graphics/shaders/upscaling/2021/09/11/amd-fsr-demystified.html)
- [Tom's Hardware: Test der FSR-Leistung und Bildqualität](https://www.tomshardware.com/news/amd-fidelityfx-super-resolution-fsr-performance-tested)
- [guru3D-Forumsthread: FSR 1 ist großartig für das, was es ist](https://forums.guru3d.com/threads/fsr-1-is-great-actually-for-what-it-is.453779/)
- [Reddit-Thread, warum hochskaliertes Filmmaterial unscharf aussehen kann](https://www.reddit.com/r/premiere/comments/1asd5id/scaling_up_video_to_a_higher_resolution_makes_it/)
- [Wikipedia-Übersicht über Bildskalierungsmethoden](https://en.wikipedia.org/wiki/Image_scaling)

## Fertig mit Hochskalieren? Verfeinern Sie den gesamten Schnitt

Öffnen Sie Ihr hochskaliertes MP4 in GrepCut Studio, um die Timeline zu schneiden, Untertitel hinzuzufügen, das Aussehen anzupassen und das endgültige Video in Ihrem Browser zu exportieren.

## Verwandte Werkzeuge

- [Video-Größe ändern](https://grepcut.com/de/tools/resize-video) - Skalieren Sie Ihren Clip prozentual.
- [Video-Geschwindigkeit ändern](https://grepcut.com/de/tools/change-video-speed) - Verlangsamen oder beschleunigen Sie Ihr Filmmaterial.
- [Video unscharf machen](https://grepcut.com/de/tools/blur-video) - Weichzeichnen Sie Hintergründe oder verbergen Sie sensible Bereiche.
