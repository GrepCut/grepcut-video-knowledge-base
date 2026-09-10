# Normalizator głośności dźwięku online

Zmierz zintegrowaną głośność i normalizuj swoje utwory do -14, -16 lub -23 LUFS. Działa w całości w przeglądarce, bez przesyłania plików i bez konta.

HTML: https://grepcut.com/pl/tools/audio-normalizer

## Jak normalizować głośność dźwięku online

1. **Prześlij swój dźwięk**: Upuść plik MP3, WAV, M4A lub OGG w polu do przesyłania.
2. **Wybierz docelowy LUFS**: Wybierz Streaming przy -14 LUFS, Podcast przy -16 LUFS lub Broadcast przy -23 LUFS.
3. **Normalizuj i eksportuj WAV**: Kliknij Normalizuj, aby zmierzyć głośność, zastosować bezpieczne wzmocnienie z ogranicznikiem szczytów i pobrać kopię WAV.

Twój plik jest przetwarzany lokalnie w przeglądarce. Nic nie jest przesyłane do GrepCut.

## Dlaczego Twój dźwięk potrzebuje LUFS, a nie tylko normalizacji szczytowej

Jeśli Twój klip osiąga szczyty blisko 0 dB, ale brzmi cicho w porównaniu z innym dźwiękiem, normalizacja szczytowa nie rozwiąże prawdziwego problemu. Szczyty pokazują tylko najgłośniejszą próbkę, podczas gdy LUFS szacuje, jak głośny jest Twój utwór w czasie.

GrepCut mierzy zintegrowaną głośność z ważeniem K, a następnie stosuje wzmocnienie w kierunku wybranego celu, respektując pułap szczytowy -1 dBTP. Pomaga to dopasować dźwięk do docelowej głośności dla streamingu, podcastu lub transmisji, bez wprowadzania szczytów w przesterowanie.

### Użyj tego, gdy chcesz uzyskać spójną postrzeganą głośność przed udostępnieniem, publikacją lub dalszą edycją.

Jeśli Twój plik jest już bardzo głośny i nie ma zapasu, pułap szczytowy może uniemożliwić osiągnięcie dokładnego celu LUFS. W takim przypadku bezpieczniejszy wynik jest zwykle lepszy niż przesterowany.

## Który cel LUFS wybrać?

| Cel | Najlepsze dla | Co robi |
| --- | --- | --- |
| -14 LUFS | Streaming wideo lub podglądy muzyki | Popularny cel głośności, gdy chcesz, aby dźwięk był zbliżony do poziomów odtwarzania głównych platform streamingowych. |
| -16 LUFS | Podcasty i klipy mówione | Praktyczny cel dla treści głosowych, gdzie klarowność i spójność są ważniejsze niż maksymalna głośność. |
| -23 LUFS | Materiały w standardzie broadcast | Cichszy cel zgodny z zaleceniami EBU R128 dla transmisji. |

Te ustawienia są punktami wyjścia. Twoja docelowa platforma może zastosować własną normalizację odtwarzania po publikacji.

## Co dzieje się w Twojej przeglądarce

Po dodaniu pliku przeglądarka dekoduje dźwięk, aby GrepCut mógł przeanalizować przebieg. Narzędzie mierzy głośność w całym utworze, oblicza potrzebne wzmocnienie dla wybranego celu LUFS i ogranicza wynik, aby szczyty pozostały poniżej pułapu.

Ponieważ przetwarzanie odbywa się lokalnie, Twój dźwięk pozostaje na Twoim urządzeniu. Bardzo długie pliki mogą wymagać więcej czasu, ponieważ przeglądarka musi zdekodować i przetworzyć dźwięk w pamięci.

- **Prywatność z założenia**: Twój źródłowy dźwięk nie jest przesyłany na serwer.
- **Świadomość LUFS**: Narzędzie celuje w postrzeganą głośność, a nie tylko w najwyższy szczyt próbki.
- **Eksport WAV**: Znormalizowany wynik jest pobierany jako plik WAV do edycji, archiwizacji lub konwersji.

## Kiedy normalizacja głośności jest najbardziej pomocna

Użyj normalizacji LUFS, gdy Twoja notatka głosowa, segment podcastu, nagranie ekranu lub klip muzyczny brzmi znacznie ciszej lub głośniej niż reszta projektu. Jest to szczególnie przydatne przed złożeniem kilku klipów w jedną oś czasu.

W przypadku głosu możesz najpierw chcieć wyczyścić szumy, zastosować korektor, kompresję lub edytować pauzy przed normalizacją. Normalizacja głośności jest zwykle ostatnim krokiem dopasowania poziomu, a nie substytutem naprawy głośnego nagrania lub nierównego wykonania.

## Zalety i ograniczenia normalizatora dźwięku

### Advantages

- Możesz normalizować MP3, WAV, M4A lub OGG bez przesyłania pliku.
- Możesz wybrać wyraźne ustawienia LUFS dla streamingu, podcastu lub transmisji.
- Ogranicznik szczytów zmniejsza ryzyko przesterowania przy dodawaniu wzmocnienia.

### Disadvantages

- Format eksportu to WAV, a nie MP3 lub M4A.
- Plik bez zapasu może nie osiągnąć dokładnego celu LUFS bez przesterowania.
- Obsługa dekodowania w przeglądarce może się różnić w zależności od kodeka pliku i urządzenia.

> Normalizacja dostosowuje każdy utwór do tego samego poziomu szczytowego, ale to nie to samo co dostosowanie ich do tego samego poziomu głośności.
>
> Reddit r/audioengineering

## FAQ normalizatora dźwięku

### Czy mogę znormalizować dźwięk do -14 LUFS online?

Tak. Wybierz ustawienie Streaming, aby celować w -14 LUFS, a następnie wyeksportuj znormalizowany wynik jako WAV. Twoja przeglądarka wykonuje przetwarzanie lokalnie, więc plik nie jest przesyłany.

### Czy powinienem użyć -14 LUFS czy -16 LUFS?

Użyj -14 LUFS, gdy chcesz typowy cel dla streamingu. Użyj -16 LUFS, gdy przygotowujesz dźwięk mówiony, np. segment podcastu. Jeśli nie jesteś pewien, wybierz ustawienie odpowiadające miejscu, w którym dźwięk będzie używany.

### Czy mogę znormalizować dźwięk do głośności transmisyjnej?

Tak. Wybierz ustawienie Broadcast, aby celować w -23 LUFS. Jest to przydatne, gdy chcesz cichszy cel głośności w stylu transmisji zamiast streamingu lub podcastu.

### Czy mój plik dźwiękowy zostanie przesłany?

Nie. GrepCut przetwarza dźwięk w Twojej przeglądarce. Plik źródłowy pozostaje na Twoim urządzeniu, a znormalizowany plik WAV jest generowany lokalnie.

### Czy normalizacja głośności zniekształci mój dźwięk?

Narzędzie stosuje wzmocnienie z pułapem szczytowym -1 dBTP, aby zmniejszyć ryzyko przesterowania. Jeśli źródło jest już bardzo głośne, ogranicznik może uniemożliwić osiągnięcie dokładnego celu LUFS, aby eksport był bezpieczniejszy.

### Dlaczego mój plik nadal brzmi inaczej po dopasowaniu LUFS?

LUFS jest silnym wskaźnikiem głośności, ale ton, bas, kompresja, szum tła i zakres dynamiczny nadal wpływają na to, jak głośny wydaje się dźwięk. Dwa pliki mogą mieć tę samą wartość LUFS, ale brzmieć inaczej.

### Czy mogę wyeksportować MP3 po normalizacji?

To narzędzie eksportuje WAV. Jeśli potrzebujesz innego formatu, najpierw znormalizuj, a następnie przekonwertuj plik WAV za pomocą osobnego konwertera.

## Źródła i dalsze czytanie

- [Dyskusja na Reddicie o normalizacji głośności podcastów](https://www.reddit.com/r/podcasts/comments/f1fbew/editing_question_do_you_normalize_and_if_so_how/)
- [Dyskusja na Reddicie o normalizacji szczytowej a postrzeganej głośności](https://www.reddit.com/r/audioengineering/comments/kctip9/normalising_the_volume_of_100_tracks_at_once/)
- [Przewodnik Spotify po normalizacji głośności](https://support.spotify.com/us/artists/article/loudness-normalization/)
- [Zalecenie ITU-R BS.1770-5 dotyczące głośności i prawdziwego szczytu](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1770-5-202311-I!!PDF-E.pdf)
- [Przegląd Web Audio API na MDN](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [Dokumentacja decodeAudioData na MDN](https://developer.mozilla.org/en-US/docs/Web/API/BaseAudioContext/decodeAudioData)

## Normalizuj swój dźwięk prywatnie

Otwórz normalizator dźwięku, wybierz docelowy LUFS i wyeksportuj czysty plik WAV bez wysyłania pliku na serwer.

## Powiązane narzędzia

- [Usuwanie szumów audio](https://grepcut.com/pl/tools/audio-noise-remover) - Oczyść szum tła przed normalizacją głośności.
- [Kreator dzwonków](https://grepcut.com/pl/tools/ringtone-maker) - Przytnij krótki klip i wyeksportuj dzwonek M4R lub MP3.
