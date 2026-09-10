# Automatyczne rozmywanie twarzy w filmie

MediaPipe BlazeFace wykrywa twarze klatka po klatce i nakłada rozmycie zapewniające prywatność. Anonimizuj tłumy, wywiady lub materiały dodatkowe bez ręcznego maskowania.

HTML: https://grepcut.com/pl/tools/face-blur

## Dla najlepszych rezultatów

Auto Face Blur działa najlepiej z filmami krótszymi niż minuta i stabilnym ruchem kamery lub obiektu. Klipy z nagłymi panoramami, szybkimi obrotami głowy lub gwałtownym ruchem mogą częściej tracić twarze między klatkami, więc przed udostępnieniem wrażliwego materiału przejrzyj eksport.

## Jak automatycznie rozmyć twarze w filmie

1. **Wybierz plik wideo**: Upuść materiał z wywiadu, wydarzenia, klasy, nagrania ekranu lub miejsca publicznego.
2. **Uruchom wykrywanie twarzy**: MediaPipe BlazeFace wykrywa twarze na Twoim urządzeniu, klatka po klatce, bez wysyłania materiału na serwer w chmurze.
3. **Sprawdź rozmycie**: Upewnij się, że każda widoczna twarz, którą chcesz ukryć, jest zakryta, szczególnie w zatłoczonych, szybko poruszających się lub słabo oświetlonych ujęciach.
4. **Eksportuj MP4**: Pobierz film z rozmyciem gaussowskim zastosowanym do każdej wykrytej twarzy.

Ponieważ przetwarzanie odbywa się w przeglądarce, Twój film pozostaje na urządzeniu, podczas gdy przygotowujesz nadający się do udostępnienia, dbający o prywatność eksport.

## Dlaczego automatyczne rozmywanie twarzy oszczędza ręczne maskowanie

Jeśli kiedykolwiek próbowałeś ukryć poruszającą się twarz ręczną maską, wiesz, jak żmudne jest to zadanie: maska musi podążać za twarzą w całym ujęciu. Robi się to trudniejsze, gdy obiekt odwraca się, przechodzi za inną osobą lub porusza się w zatłoczonej scenie.

Auto Face Blur jest stworzone do tej powtarzalnej pracy związanej z prywatnością. Przesyłasz klip, przeglądarka wykrywa twarze za pomocą lokalnego AI, a GrepCut stosuje rozmycie do wykrytych obszarów twarzy, dzięki czemu nie musisz ręcznie klatkować każdego ruchu.

### Użyj go, gdy potrzebujesz prywatności przed udostępnieniem

- **Wywiady uliczne**: Ukryj przechodniów przed opublikowaniem klipu nagranego w miejscu publicznym.
- **Materiał z klasy lub warsztatów**: Zmniejsz ekspozycję tożsamości przed udostępnieniem nagrania szerszej grupie.
- **Filmy podsumowujące wydarzenia**: Rozmyj twarze w ujęciach tłumu, gdzie nie chcesz, aby każda osoba była rozpoznawalna.
- **Klipy twórców**: Chroń nieznajomych, nieletnich lub gości w tle przed opublikowaniem krótkich filmów.

To narzędzie koncentruje się na twarzach. Jeśli potrzebujesz ocenzurować znak, tablicę, ekran, identyfikator lub inny stały obszar, użyj zamiast tego [Rozmycie obszaru](/tools/blur-region-video).

## Auto Face Blur vs Ręczne maskowanie vs Narzędzia chmurowe

| Metoda | Najlepsze do | Kompromis |
| --- | --- | --- |
| Auto face blur w GrepCut | Szybkie ukrywanie wykrytych twarzy w przeglądarce | Nadal musisz sprawdzić wynik pod kątem pominiętych lub częściowo widocznych twarzy |
| Ręczne śledzenie maski | Precyzyjna kontrola nad jedną twarzą lub jednym niestandardowym obszarem | Może być konieczne dostosowanie masek klatka po klatce, gdy zmienia się ruch |
| Narzędzia do anonimizacji w chmurze | Zadania po stronie serwera lub zespołowe procesy przeglądu | Twój materiał zwykle opuszcza urządzenie, co może nie być odpowiednie dla wrażliwych treści |

Wybierz przepływ pracy odpowiadający Twojemu poziomowi ryzyka. W przypadku wrażliwych materiałów lub objętych RODO, lokalne przetwarzanie w przeglądarce pomaga uniknąć przesyłania surowego wideo na serwer strony trzeciej.

## Co wykrywanie twarzy może i czego nie może zagwarantować

Wykrywanie twarzy działa najlepiej, gdy twarze są widoczne, odpowiednio duże i nie są mocno zasłonięte. Twarz odwrócona, zakryta dłonią, przycięta na krawędzi lub rozmazana przez ruch może być trudniejsza do wykrycia w każdej klatce.

Przed publikacją przejrzyj swój eksport i poszukaj pominiętych twarzy, odbić, identyfikatorów, tablic rejestracyjnych, ekranów, głosów lub innych identyfikatorów. Rozmywanie twarzy zmniejsza wizualną identyfikowalność, ale nie usuwa automatycznie każdego ryzyka prywatności w filmie.

### W przypadku wrażliwego udostępniania sprawdź więcej niż twarz

- **Małe twarze**: Małe twarze w tle mogą być trudniejsze do konsekwentnego wykrycia.
- **Szybki ruch**: Rozmycie ruchu i szybkie panoramy kamery mogą sprawić, że wykrywanie będzie mniej niezawodne.
- **Inne identyfikatory**: Rozmycie twarzy nie ukryje nazwisk, identyfikatorów, tatuaży, tablic, ekranów ani dźwięku.

Jeśli Twój klip zawiera wrażliwe materiały prawne, medyczne, w miejscu pracy, szkole lub sektorze publicznym, traktuj to jako pomoc w edycji i potwierdź swoje obowiązki w zakresie prywatności przed dystrybucją.

## Zalety i ograniczenia rozmywania twarzy w przeglądarce

### Advantages

- Twój surowy film pozostaje na urządzeniu podczas przetwarzania
- Wiele wykrytych twarzy może być rozmytych w tej samej klatce
- Unikasz instalowania pełnego edytora wideo do prostego zadania prywatności
- Eksportowany plik MP4 jest gotowy do udostępnienia po sprawdzeniu

### Disadvantages

- Wykrywanie twarzy może pominąć ukryte, małe, profilowe lub szybko poruszające się twarze
- Automatycznie celuje w twarze, a nie w tablice rejestracyjne, ekrany czy tekst
- Duże lub długie filmy zależą od wydajności urządzenia i przeglądarki
- Rozmycie gaussowskie samo w sobie nie jest kompletną gwarancją anonimizacji prawnej

## FAQ - Rozmywanie twarzy

### Czy można rozmyć wiele twarzy w jednym filmie?

Tak. GrepCut stosuje rozmycie do każdej twarzy wykrytej w każdej klatce, więc ujęcie tłumu lub wywiadu może mieć więcej niż jedną rozmytą twarz.

### Czy mój film zostanie przesłany?

Nie. Wykrywanie twarzy i renderowanie odbywają się lokalnie w Twojej przeglądarce, więc surowy film nie musi opuszczać Twojego urządzenia.

### Czy można rozmyć tylko wybraną twarz?

To narzędzie jest przeznaczone do automatycznego rozmywania wykrytych twarzy. Jeśli potrzebujesz celować tylko w określony stały obszar, użyj [Rozmycie obszaru](/tools/blur-region-video).

### Czy rozmyje twarze, które się poruszają?

Tak, narzędzie analizuje klatki i stosuje rozmycie tam, gdzie twarze są wykrywane podczas ruchu. Nadal powinieneś sprawdzić eksport, ponieważ szybki ruch, zasłonięcie lub bardzo małe twarze mogą wpłynąć na wykrywanie.

### Czy mogę rozmyć tablice rejestracyjne lub tekst tym narzędziem?

Nie automatycznie. Auto Face Blur koncentruje się na twarzach. W przypadku tablic, znaków, ekranów lub innych obszarów użyj [Rozmycie obszaru](/tools/blur-region-video) lub [Pikselizacja wideo](/tools/pixelate-video).

### Czy rozmycie twarzy wystarcza do materiałów objętych RODO?

Może pomóc zmniejszyć identyfikowalność, zwłaszcza że film pozostaje lokalny, ale nie jest to porada prawna ani gwarancja pełnej anonimizacji. Przed udostępnieniem sprawdź eksportowany film pod kątem innych identyfikatorów.

### Dlaczego twarz może zostać pominięta?

Twarz może być zbyt mała, odwrócona, częściowo zakryta, przycięta przez kadr lub rozmazana przez ruch. Jeśli klip jest wrażliwy, przejrzyj cały eksport przed publikacją.

## Źródła i dalsze czytanie

- [Dyskusja na Reddicie o praktycznym śledzeniu rozmycia twarzy w edytorach wideo](https://www.reddit.com/r/VideoEditing/comments/12o8bpq/good_ways_to_blur_faces_in_video/)
- [Wątek na Super User o rozmywaniu poruszającej się twarzy ze zmieniającymi się współrzędnymi](https://superuser.com/questions/1704283/how-to-apply-an-ffmpeg-filter-to-a-moving-object)
- [Wątek na Reddicie z prośbą o aplikacje do automatycznego rozmywania twarzy](https://www.reddit.com/r/VideoEditing/comments/1d8cx08/looking_for_apps_that_automatically_blurs_faces/)
- [Przewodnik Google MediaPipe Face Detector dla sieci](https://developers.google.com/edge/mediapipe/solutions/vision/face_detector/web_js)
- [Przegląd wykrywania twarzy MediaPipe oparty na BlazeFace](https://mediapipe.readthedocs.io/en/latest/solutions/face_detection.html)
- [Wytyczne ICO dotyczące skutecznej anonimizacji i maskowania nagrań wideo](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/data-sharing/anonymisation/how-do-we-ensure-anonymisation-is-effective/)

## Rozmywaj twarze bez przesyłania filmu

Otwórz GrepCut, upuść swój klip i utwórz film z rozmytymi twarzami bezpośrednio w przeglądarce. Twój materiał pozostaje lokalny, podczas gdy przygotowujesz dbający o prywatność eksport.

## Powiązane narzędzia

- [Rozmycie obszaru](https://grepcut.com/pl/tools/blur-region-video) - ręcznie ukryj stały obszar, taki jak tablica, znak lub ekran.
- [Pikselizacja wideo](https://grepcut.com/pl/tools/pixelate-video) - pikselizuj cały klip mozaiką blokową.
- [Przycinanie wideo](https://grepcut.com/pl/tools/video-trimmer) - wytnij prywatne lub nieistotne części przed eksportem.
