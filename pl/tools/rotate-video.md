# Obróć wideo online

Obróć nagranie z telefonu do pionu lub przewróć klip na potrzeby postów w mediach społecznościowych. Przetwarzane lokalnie w przeglądarce - bez wysyłania i bez znaku wodnego.

HTML: https://grepcut.com/pl/tools/rotate-video

## Jak obrócić wideo w przeglądarce

1. **Dodaj wideo**: Przeciągnij plik MP4, MOV, WebM, MKV lub M4V do narzędzia lub kliknij, aby przeglądać. Plik pozostaje na Twoim urządzeniu, a przeglądarka przygotowuje podgląd.
2. **Wybierz kąt**: Wybierz 90° zgodnie z ruchem wskazówek zegara, 180° lub 90° przeciwnie do ruchu wskazówek zegara. Użyj podglądu, aby sprawdzić, czy nagranie z telefonu jest pionowe przed eksportem.
3. **Wybierz tryb eksportu**: Użyj trybu Social-ready, gdy chcesz zapisać obrót bezpośrednio w pikselach, albo Fast remux, gdy wystarczy zmiana flagi obrotu MP4.
4. **Pobierz MP4**: Kliknij Obróć, aby wyeksportować poprawione wideo jako MP4. Możesz też otworzyć klip w GrepCut Studio, jeśli potrzebujesz przycięcia, zmiany rozmiaru, napisów lub edycji na osi czasu.

Potrzebujesz więcej niż obrót? Otwórz swój klip w [GrepCut Studio](/) i kontynuuj edycję w przeglądarce.

## Dlaczego wideo z telefonu wygląda pionowo

Wideo z telefonu może wyglądać poprawnie w galerii, ale być pionowe w innej aplikacji, ponieważ plik może przechowywać flagę obrotu zamiast pionowych pikseli. Gdy odtwarzacz lub program do przesyłania respektuje tę flagę, klip wygląda dobrze. Gdy ją ignoruje, wideo wydaje się obrócone, mimo że samo nagranie nie jest uszkodzone.

GrepCut oferuje dwa rozwiązania tego problemu. Tryb Social-ready fizycznie obraca klatki i usuwa flagę obrotu, co jest bezpieczniejszym wyborem przed publikacją. Fast remux zachowuje oryginalny strumień wideo i aktualizuje metadane obrotu, co jest szybsze, ale zależy od tego, czy następna aplikacja poprawnie odczyta flagę.

### Użyj tego, gdy:

- **Nagranie z telefonu jest pionowe**: Obróć pionowe lub poziome nagranie przed przesłaniem.
- **Wideo jest do góry nogami**: Obróć o 180°, gdy orientacja kamery była nieprawidłowa podczas nagrywania.
- **Aplikacja ignoruje metadane obrotu**: Wbuduj obrót w piksele, aby wynik nie opierał się na ukrytej fladze.
- **Potrzebujesz szybkiego eksportu MP4**: Zapisz poprawione MP4 bez otwierania desktopowego edytora wideo.

Jeśli publikujesz na Instagramie, TikToku, YouTube lub innym serwisie, który może ponownie przetworzyć plik, wybierz **Social-ready**, aby uzyskać najbardziej przewidywalny wynik.

## Social-ready vs Fast remux

| Potrzeba | Social-ready | Fast remux |
| --- | --- | --- |
| Co się zmienia | Obraca rzeczywiste klatki wideo i usuwa flagę obrotu | Zachowuje oryginalne klatki i aktualizuje metadane obrotu MP4 |
| Szybkość | Wolniejsze, ponieważ wideo jest ponownie kodowane do H.264 | Prawie natychmiastowe, ponieważ skompresowane pakiety wideo są kopiowane |
| Jakość | Eksport H.264 wysokiej jakości, ale to wciąż ponowne kodowanie | Identyczny z oryginalnym strumieniem wideo |
| Najlepsze do publikacji w mediach społecznościowych | Najlepszy wybór, gdy następna aplikacja może ignorować metadane obrotu | Działa tylko wtedy, gdy następna aplikacja respektuje flagę obrotu |
| Wynik | Pionowe piksele w pliku MP4 | Te same piksele z poprawioną instrukcją obrotu |

Oba tryby działają lokalnie w przeglądarce. Twoje oryginalne wideo nie jest przesyłane, a eksport nie zawiera znaku wodnego.

## Kiedy ponownie kodować zamiast muxować

Fast remux przydaje się, gdy chcesz szybko poprawić plik lokalnie i wiesz, że następny odtwarzacz odczytuje metadane obrotu MP4. To dobry wybór do podglądu, archiwizacji lub wysłania pliku do aplikacji, która poprawnie obsługuje flagi obrotu.

Social-ready jest lepszy, gdy klip będzie przesyłany, ponownie kompresowany lub otwierany na różnych urządzeniach. Zapisując pionowe piksele w MP4, eliminujesz zgadywanie. Eksport może trwać dłużej, ale plik jest łatwiejszy do poprawnego wyświetlenia przez platformy społecznościowe i podstawowe odtwarzacze.

### Prosta zasada:

Jeśli wideo jest do publikacji, wybierz **Social-ready**. Jeśli plik ma zostać na Twoim urządzeniu i chcesz go poprawić jak najszybciej, wypróbuj **Fast remux**.

## Obrót wideo w skrócie

### Advantages

- Prywatne przetwarzanie bez przesyłania na serwer.
- Opcje obrotu 90°, 180° i 270°.
- Eksport MP4 Social-ready dla przewidywalnej orientacji.
- Opcja Fast remux, gdy potrzebujesz tylko poprawki metadanych.
- Darmowy eksport bez znaku wodnego.

### Disadvantages

- Tryb Social-ready ponownie koduje wideo, więc eksport trwa dłużej niż remux.
- Fast remux zależy od tego, czy następna aplikacja honoruje metadane obrotu.
- Obsługiwany jest tylko obrót o kąty proste, a nie dowolne kąty.
- Wymaga nowoczesnej przeglądarki z obsługą WebCodecs.

> obserwowane przez niektóre odtwarzacze, a przez inne nie
>
> Dyskusja na Stack Overflow o metadanych obrotu MP4

## Obrót wideo - FAQ

### Czy mogę obrócić wideo bez przesyłania go?

Tak. GrepCut przeprowadza proces obracania w przeglądarce, więc plik pozostaje na Twoim urządzeniu, zamiast być przesyłany na serwer.

### Dlaczego moje MP4 wygląda pionowo w jednej aplikacji, a poprawnie w innej?

Twoje MP4 może zawierać metadane obrotu. Niektóre odtwarzacze odczytują tę instrukcję i obracają wideo podczas odtwarzania, podczas gdy inne aplikacje ją ignorują. Użyj trybu **Social-ready**, gdy chcesz, aby wyeksportowane MP4 zawierało pionowe piksele zamiast polegać na metadanych.

### Czy powinienem użyć Social-ready czy Fast remux?

Użyj **Social-ready**, gdy planujesz opublikować klip online lub wysłać go do aplikacji, która może ignorować flagi obrotu. Użyj **Fast remux**, gdy chcesz najszybszego eksportu, a następny odtwarzacz prawdopodobnie honoruje metadane obrotu MP4.

### Czy obrót wideo obniży jakość?

Fast remux pozostawia oryginalny strumień wideo bez zmian, więc strumień wideo pozostaje identyczny. Tryb Social-ready ponownie koduje do H.264, aby obrót został wbudowany w piksele, co jest bardziej niezawodne do publikacji, ale trwa dłużej.

### Jakie formaty wideo można obracać?

Możesz dodać MP4, MOV, WebM, MKV, M4V i większość popularnych formatów wideo. GrepCut eksportuje obrócony wynik jako MP4.

### Czy dźwięk pozostanie zsynchronizowany po obrocie?

Tak. Obrót nie zmienia prędkości odtwarzania. Audio jest kopiowane bezstratnie, jeśli jest już w formacie AAC, lub ponownie kodowane do AAC dla szerokiej kompatybilności z MP4.

### Czy mogę obrócić o niestandardowy kąt, np. 12°?

Nie. To narzędzie jest przeznaczone do obrotu o kąty proste: 90° zgodnie z ruchem wskazówek zegara, 180° i 90° przeciwnie do ruchu wskazówek zegara. W przypadku pionowych nagrań z telefonu zwykle są to potrzebne poprawki.

### Dlaczego GrepCut wymaga nowoczesnej przeglądarki?

Eksport Social-ready zależy od funkcji przetwarzania wideo w przeglądarce, takich jak WebCodecs. Jeśli Twoja przeglądarka nie obsługuje wymaganych API, spróbuj zaktualizować przeglądarkę opartą na Chromium.

## Źródła i dalsze czytanie

- [Dyskusja na Reddit o przypadkowym nagrywaniu w trybie pionowym](https://www.reddit.com/r/VideoEditing/comments/xryq3n/i_accidentally_filmed_my_videos_in_portrait_mode/)
- [Pytanie na Reddit o obracanie bez ponownego kodowania](https://www.reddit.com/r/VideoEditing/comments/uuw62f/automatically_rotate_video_without_actually/)
- [Wyjaśnienie metadanych obrotu wideo iPhone na Super User](https://superuser.com/questions/564233/iphone-recorded-videos-getting-rotated-on-windows-systems)
- [Dyskusja na Stack Overflow o flagach obrotu MP4](https://stackoverflow.com/questions/69386275/mp4-and-rotation-remove-flags-but-set-rotation)
- [Przewodnik MDN po API WebCodecs](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [Specyfikacja W3C WebCodecs](https://www.w3.org/TR/webcodecs/)

## Skończyłeś obracać? Zbuduj pełną edycję

Otwórz GrepCut Studio, aby przyciąć, zmienić rozmiar, dodać napisy, dodać muzykę i zakończyć edycję wideo w przeglądarce.

## Powiązane narzędzia

- [Przytnij wideo](https://grepcut.com/pl/tools/crop-video) - przytnij kadr do regionu lub proporcji.
- [Zmień rozmiar wideo](https://grepcut.com/pl/tools/resize-video) - skaluj klip procentowo.
- [Przycinacz wideo](https://grepcut.com/pl/tools/video-trimmer) - przytnij klip przed lub po obrocie.
