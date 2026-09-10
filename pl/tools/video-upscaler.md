# Darmowy internetowy skalowacz wideo FSR

Zwiększ rozdzielczość klipów dzięki adaptacyjnemu skalowaniu FSR w przeglądarce.

HTML: https://grepcut.com/pl/tools/video-upscaler

## Przeczytaj to najpierw: FSR wyostrza krawędzie, nie tworzy szczegółów

Ustaw oczekiwania przed rozpoczęciem. FSR czyści krawędzie podczas powiększania klipu, ale w przypadku materiału, który jest już miękki, niskiej jakości lub nieostry, poprawa jest często marginalna, ponieważ jest bardzo mało rzeczywistych informacji o krawędziach do odtworzenia.

FSR to upscaler przestrzenny, a nie AI. Nie może dodać szczegółów, które nigdy nie zostały uchwycone. Odtworzenie tekstury, której nie ma w źródle, wymaga modelu AI super-rozdzielczości, co jest innym rodzajem narzędzia. Użyj tego upscalera, aby czysto powiększyć i wyostrzyć krawędzie, a nie odzyskać utracone szczegóły.

## Jak powiększyć wideo online w przeglądarce

1. **Prześlij swój klip**: Upuść plik MP4, MOV, WebM lub MKV na obszar przesyłania.
2. **Wybierz 2×, 3× lub 4×**: Wybierz współczynnik powiększenia pasujący do Twojej osi czasu, eksportu społecznościowego lub układu HD.
3. **Eksportuj MP4**: Pobierz powiększone MP4 lub otwórz je w GrepCut Studio, aby dodać napisy, przyciąć i wykończyć.

Powiększanie odbywa się lokalnie w przeglądarce, więc wideo pozostaje na Twoim urządzeniu.

## Użyj FSR Upscaling, gdy Twój klip jest za mały

Jeśli Twój klip został nagrany w 480p, 720p lub w małym oknie przechwytywania ekranu, może wyglądać za mało w edycji HD. Powiększanie zwiększa wymiary pikseli przed eksportem, więc wideo pasuje do osi czasu 1080p, przesyłki na YouTube lub ustawień społecznościowych bez ręcznego rozciągania w innym edytorze.

GrepCut powiększa z FSR (AMD FidelityFX Super Resolution). Zamiast zwykłego gładkiego rozciągnięcia, FSR odtwarza krawędzie podczas powiększania, dzięki czemu linie i kontury pozostają ostrzejsze niż w przypadku skalowania dwusześciennego. To czyni go praktycznym wyborem dla skompresowanych nagrań z telefonu, klipów instruktażowych i repostów, które zostały wyeksportowane za małe.

### Najlepsze do:

- **Stare nagrania z telefonu**: Przybliż klip 480p lub 720p do układu HD z czystszymi krawędziami przed publikacją.
- **Nagrania ekranu**: Spraw, by małe okno przechwytywania było łatwiejsze do umieszczenia w edycji instruktażowej lub prezentacyjnej.
- **Reposty społecznościowe**: Zmień rozmiar pionowych klipów, które wróciły z innej aplikacji w niższej rozdzielczości.

## Jak działa FSR Upscaling i co może, a czego nie może naprawić

FSR to upscaler przestrzenny: działa na pojedynczej klatce przed sobą, bez wektorów ruchu, bufora głębi ani modelu AI. Działa w dwóch przejściach GPU. Najpierw EASU (Edge-Adaptive Spatial Upsampling) próbkuje klatkę w sposób uwzględniający kierunek, wykrywając, jak różnią się sąsiednie gradienty, aby krawędzie zostały odtworzone, a nie tylko rozmyte. Następnie RCAS (Robust Contrast-Adaptive Sharpening) dodaje kontrolowane wyostrzenie, które podbija szczegóły bez tworzenia efektu halo lub wzmacniania szumów.

Ponieważ FSR używa zwykłych shaderów i nigdy nie patrzy na inne klatki, traktuje każdą klatkę tak samo i utrzymuje spójność eksportu. Nie jest to jednak super-rozdzielczość AI. Jeśli źródło jest mocno rozmyte, silnie skompresowane lub brakuje mu drobnych szczegółów, FSR może dopasować większą klatkę z ostrzejszymi krawędziami, ale nie może odtworzyć tekstury, która nigdy nie została uchwycona.

### Pod maską:

- **EASU**: Adaptacyjne próbkowanie krawędzi, które odtwarza krawędzie podczas powiększania, ostrzejsze niż dwuliniowe lub dwusześcienne.
- **RCAS**: Kontrastowo-adaptacyjne wyostrzenie, stosowane automatycznie, które dodaje ostrości rzeczywistym krawędziom, pozostawiając płaskie obszary bez zmian.

W przypadku bardzo miękkiego materiału najpierw wykonaj krótki test eksportu. Jeśli podgląd już wygląda zbyt miękko, mniejszy współczynnik często wygląda bardziej naturalnie niż mocne rozciągnięcie 4×.

## Jak FSR wypada w porównaniu ze zwykłym skalowaniem

| Metoda | Jak skaluje | Typowy wynik |
| --- | --- | --- |
| Najbliższy sąsiad | Powiela najbliższy piksel. | Blokowe, twarde, schodkowe krawędzie. |
| Dwuliniowe lub dwusześcienne | Uśrednia sąsiednie piksele. | Gładsze, ale krawędzie wyglądają miękko. |
| FSR (EASU + RCAS) | Adaptacyjne próbkowanie krawędzi plus kontrastowo-adaptacyjne wyostrzenie. | Czystsze, ostrzejsze krawędzie bez modelu AI. |

FSR odtwarza krawędzie, a nie tylko je wygładza, ale jak każda metoda przestrzenna działa ze szczegółami już obecnymi w klipie.

## Który współczynnik powiększenia wybrać?

Właściwy współczynnik zależy od tego, jak daleko Twój klip jest od potrzebnego rozmiaru. Większe współczynniki tworzą więcej pikseli do odtworzenia, więc miękkie źródło szybciej pokazuje swoje ograniczenia przy 4× niż przy 2×.

### Wybierz swój współczynnik:

- **2×**: Bezpieczny pierwszy test, gdy klip potrzebuje tylko umiarkowanego zwiększenia rozmiaru.
- **3×**: Przydatny, gdy mały klip musi wypełnić więcej płótna HD.
- **4×**: Najlepszy dla krótkich klipów, gdzie potrzebujesz maksymalnych wymiarów i możesz trochę poczekać.

Zacznij od 2×, gdy nie jesteś pewien, a następnie spróbuj ponownie z większym współczynnikiem, jeśli źródło ma wystarczająco dużo szczegółów.

## Podgląd odpowiada eksportowi

FSR powiększa i wyostrza automatycznie, więc nie ma nic do konfigurowania. Wybierz współczynnik, sprawdź wynik i eksportuj. EASU obsługuje adaptacyjne powiększanie krawędzi, a RCAS dodaje stałe, gustowne wyostrzenie na wierzchu.

Podgląd przed i po używa tego samego potoku FSR co eksport, więc to, co widzisz, trafia do Twojego MP4. Powiększ podgląd, aby ocenić ostrość krawędzi przed zatwierdzeniem pełnego renderowania.

Jeśli podgląd nadal wygląda miękko po powiększeniu, zwykle oznacza to, że szczegółów nie było w źródle, a niższy współczynnik może wyglądać bardziej naturalnie.

## Zachowaj prywatność wideo podczas testowania

Narzędzia wideo online często wymagają przesłania całego pliku, zanim zobaczysz wynik. Ten upscaler działa w przeglądarce, więc materiał nie opuszcza urządzenia podczas przetwarzania.

Jest to przydatne, gdy klip zawiera prywatne treści ekranowe, nieopublikowane materiały społecznościowe, szkice klientów lub nagrania z zajęć. Możesz przetestować współczynnik, pobrać MP4 i kontynuować edycję bez wysyłania oryginalnego pliku na serwer.

Dłuższe klipy i eksporty 4× zależą od szybkości urządzenia. W przypadku szybkich kontroli najpierw przytnij klip lub przetestuj krótki fragment przed przetworzeniem całego wideo.

## Video Upscaler w skrócie

### Advantages

- Działa lokalnie w przeglądarce bez przesyłania.
- FSR odtwarza krawędzie, więc wyniki są ostrzejsze niż w przypadku skalowania dwusześciennego.
- Powiększanie EASU i wyostrzanie RCAS są stosowane automatycznie, nic do konfigurowania.
- Ustawienia 2×, 3× i 4× upraszczają wybór.
- Darmowy eksport MP4 bez znaku wodnego.

### Disadvantages

- To upscaler przestrzenny, a nie AI, więc nie może wymyślić szczegółów, które nie zostały uchwycone.
- Bardzo rozmyte lub silnie skompresowane źródła mogą nadal wyglądać miękko.
- Długie eksporty 4× mogą trwać dłużej na wolniejszych urządzeniach.
- Jeśli przeglądarka nie obsługuje WebGL2, przechodzi na zwykłe skalowanie dwusześcienne.

> FSR 1 nie patrzy na dane poprzednich klatek, aby ulepszyć swoje powiększanie, ale po prostu rozciąga każdy izolowany obraz, używając technik takich jak wykrywanie krawędzi, aby określić, jak najlepiej rozciągnąć obraz.
>
> PCGamesN

## FAQ Video Upscaler

### Czy mogę powiększyć wideo online bez przesyłania go?

Tak. Twoje wideo jest przetwarzane lokalnie w przeglądarce, więc plik pozostaje na Twoim urządzeniu.

### Czy FSR to to samo co powiększanie AI?

Nie. FSR to upscaler przestrzenny, który działa na zwykłych shaderach i opiera się na pojedynczej klatce. Odtwarza krawędzie za pomocą EASU i wyostrza za pomocą RCAS, ale nie używa sieci neuronowej, więc nie może wymyślić szczegółów tak, jak próbuje to robić super-rozdzielczość AI.

### Czym FSR różni się od skalowania dwusześciennego?

Dwusześcienne uśrednia sąsiednie piksele, co powiększa klatkę, ale pozostawia krawędzie miękkie. FSR sprawdza, jak zmieniają się sąsiednie gradienty i próbkuje wzdłuż krawędzi, dzięki czemu linie i kontury pozostają ostrzejsze, a następnie RCAS dodaje kontrolowane wyostrzenie na wierzchu.

### Czy FSR wyostrzy moje rozmyte wideo?

Może sprawić, że krawędzie będą wyglądać czyściej i dodać nieco ostrości, ale poprawa jest często marginalna w przypadku miękkiego materiału i nie może przywrócić brakujących szczegółów z rozmytego, niskiej jakości lub nieostrego źródła. Odzyskanie szczegółów, których nie ma, wymaga upscalera AI.

### Którego współczynnika powiększenia użyć?

Użyj 2× dla bezpiecznego pierwszego przejścia, 3× gdy klip potrzebuje silniejszego zwiększenia rozmiaru, a 4× dla krótkich klipów o niskiej rozdzielczości, gdzie potrzebujesz największego wyjścia.

### Czy mogę powiększyć wideo 480p do edycji 1080p?

Tak. Możesz powiększyć klip przed umieszczeniem go w osi czasu HD. FSR utrzymuje krawędzie czystsze niż zwykłe rozciągnięcie, choć wynik może nadal wyglądać bardziej miękko niż natywne wideo 1080p, ponieważ oryginał ma mniej pikseli.

### Czy muszę dostosowywać jakieś ustawienia?

Nie. FSR powiększa za pomocą EASU i wyostrza za pomocą RCAS automatycznie, więc wystarczy wybrać współczynnik i eksportować. Podgląd przed i po używa tego samego potoku co eksport.

### Jakie formaty wideo mogę importować i czy jest znak wodny?

Możesz importować pliki MP4, MOV, WebM i MKV oraz eksportować powiększone MP4 bez znaku wodnego.

## Źródła i dalsze czytanie

- [Przegląd AMD GPUOpen FidelityFX Super Resolution 1 (EASU i RCAS)](https://gpuopen.com/fidelityfx-superresolution/)
- [Podręcznik techniczny AMD GPUOpen FSR 1 dotyczący przestrzennego powiększania](https://gpuopen.com/manuals/fidelityfx_sdk/techniques/super-resolution-spatial/)
- [FidelityFX Super Resolution 1.0 wyjaśnione (przewodnik po shaderach)](https://jntesteves.github.io/shadesofnoice/graphics/shaders/upscaling/2021/09/11/amd-fsr-demystified.html)
- [Tom's Hardware: testowanie wydajności i jakości obrazu FSR](https://www.tomshardware.com/news/amd-fidelityfx-super-resolution-fsr-performance-tested)
- [Wątek na forum guru3D: FSR 1 jest świetny, biorąc pod uwagę, czym jest](https://forums.guru3d.com/threads/fsr-1-is-great-actually-for-what-it-is.453779/)
- [Wątek na Reddicie o tym, dlaczego powiększone wideo może wyglądać rozmycie](https://www.reddit.com/r/premiere/comments/1asd5id/scaling_up_video_to_a_higher_resolution_makes_it/)
- [Przegląd metod skalowania obrazu na Wikipedii](https://en.wikipedia.org/wiki/Image_scaling)

## Skończyłeś powiększanie? Dopracuj całą edycję

Otwórz powiększone MP4 w GrepCut Studio, aby przyciąć oś czasu, dodać napisy, dostosować wygląd i wyeksportować końcowe wideo w przeglądarce.

## Powiązane narzędzia

- [Zmień rozmiar wideo](https://grepcut.com/pl/tools/resize-video) - skaluj klip procentowo.
- [Zmień prędkość wideo](https://grepcut.com/pl/tools/change-video-speed) - zwolnij lub przyspiesz materiał.
- [Rozmyj wideo](https://grepcut.com/pl/tools/blur-video) - zmiękcz tła lub ukryj wrażliwe obszary.
