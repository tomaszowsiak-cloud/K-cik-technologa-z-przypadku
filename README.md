# K-cik-technologa-z-przypadku
KALKULATOR TECHNOLOGA
# Kalkulator Technologa Oczyszczalni Ścieków

**Darmowe, otwarte narzędzie do codziennych obliczeń procesowych — działa w przeglądarce, bez instalacji, bez logowania, bez wysyłania danych gdziekolwiek.**

---

## Po co to powstało

Każdy, kto pracuje przy oczyszczalni ścieków, zna ten moment: trzeba szybko policzyć wiek osadu, sprawdzić czy recyrkulacja jest ustawiona prawidłowo, albo oszacować dawkę koagulantu — a pod ręką jest kartka, długopis i pamięć do wzorów, które kiedyś się znało na pamięć.

To narzędzie zbiera **23 najczęściej używane obliczenia** technologa w jednym miejscu. Każdy kalkulator pokazuje nie tylko wynik, ale też **wzór, znaczenie symboli, zakresy referencyjne i interpretację** — czyli odpowiada na pytanie „dobrze czy źle?", a nie tylko „ile?".

Powstało z prostej potrzeby: żeby młodszy stażem technolog miał od czego zacząć, a starszy miał czym szybko zweryfikować intuicję. Bo najlepsze obliczenie to wciąż to, które rozumiesz — narzędzie ma pomagać myśleć, nie zastępować myślenie.

---

## Czym to jest (i czym NIE jest)

**To jest:** pojedynczy plik HTML, który otwierasz w dowolnej przeglądarce (komputer, telefon, tablet). Wszystkie obliczenia dzieją się lokalnie, na Twoim urządzeniu. Nic nie jest wysyłane do internetu. Historia obliczeń zapisuje się tylko w Twojej przeglądarce.

**To NIE jest:** zamiennik projektowania inżynierskiego ani oprogramowania do modelowania (typu GPS-X, SUMO, BioWin). Wyniki mają charakter pomocniczy i orientacyjny — do szybkiej oceny operacyjnej, edukacji i weryfikacji, nie do podpisywania projektów.

---

## Co potrafi — 23 kalkulatory w 6 grupach

### 1. Osad czynny — kondycja i kontrola procesu

Serce każdej oczyszczalni biologicznej. Te wskaźniki mówią, czy osad jest zdrowy i czy proces jest pod kontrolą.

- **SVI** (Indeks Objętościowy Osadu) — czy osad dobrze opada w osadniku
- **DSVI** (Rozcieńczony Indeks Osadu) — wersja wiarygodna przy wysokim stężeniu osadu, gdy zwykły SVI „kłamie" bo osad nie ma gdzie opaść w cylindrze
- **F/M** (stosunek ładunku do biomasy) — czy mikroorganizmy są „najedzone" czy „głodzone"
- **SRT / Wiek Osadu** — najważniejszy parametr kontrolny; ile dni średnio bakterie przebywają w układzie
- **HRT** (Czas Zatrzymania Hydraulicznego) — jak długo ściek płynie przez reaktor
- **Bᵥ** (Obciążenie Objętościowe) — ile ładunku przyjmuje każdy metr sześcienny reaktora
- **R — wymagana recyrkulacja** osadu z osadnika (ile osadu trzeba zawracać)
- **R — aktualna recyrkulacja** z porównaniem do wymaganej (czy operator dolewa za mało, za dużo, czy w sam raz)

### 2. Bilans tlenu i napowietrzanie — gdzie ucieka prąd

Napowietrzanie to zwykle 50–70% całego zużycia energii oczyszczalni. Tu policzysz, ile tlenu naprawdę potrzeba.

- **AOR** — zapotrzebowanie procesu na tlen (na rozkład zanieczyszczeń + nitryfikację)
- **SOR** — ile tlenu musi dostarczyć dmuchawa w warunkach standardowych (z korektą na temperaturę, zasolenie i jakość ścieku)
- **Energia napowietrzania** — szacunkowe zużycie prądu i koszt roczny w złotówkach

### 3. Strącanie chemiczne fosforu — dawkowanie koagulantów

Gdy biologia nie wystarcza do usunięcia fosforu, wspomaga się ją chemią.

- **Dawka koagulantu** — ile PIX-u, PAX-u lub siarczanu glinu dozować (z gotowym wyborem typowych produktów handlowych i przeliczeniem na litry/dobę)
- **Dodatkowy osad chemiczny** — ile osadu przybędzie z procesu strącania (bo to realny koszt zagospodarowania)

### 4. SBR — reaktory sekwencyjne (porcjowe)

Dla oczyszczalni pracujących cyklicznie zamiast w przepływie ciągłym.

- **VER** (Współczynnik Wymiany Objętości) — jaka część reaktora wymienia się w jednym cyklu
- **Liczba cykli i wydajność dobowa** — ile ścieku układ przerobi na dobę
- **Obciążenie cykliczne F/M** — wersja F/M dla pracy porcjowej

### 5. Temperatura, kinetyka i bilans biogenny

Procesy biologiczne zależą od temperatury i od proporcji składników odżywczych.

- **Korekcja temperaturowa (Arrhenius)** — jak temperatura zmienia szybkość procesów (z gotowymi współczynnikami dla rozkładu węgla, nitryfikacji, denitryfikacji)
- **Bilans biogenny C:N:P** — czy ścieki mają dobry stosunek węgla, azotu i fosforu; **z wyborem bazy węglowej: BZT₅, ChZT lub OWO** (liczysz tym, co masz akurat zmierzone w laboratorium)
- **Minimalny wiek osadu dla nitryfikacji** — jak długi SRT potrzebny, żeby bakterie nitryfikacyjne nie zostały wypłukane (kluczowe zimą)
- **Sprawność usuwania (η)** — procent redukcji zanieczyszczeń, z progami wymagań dla większych aglomeracji

### 6. Recyrkulacja wewnętrzna i denitryfikacja — usuwanie azotu

Najtrudniejsza część bilansu azotowego — jak głęboko da się zejść z azotanami.

- **Tryb 1: Ile recyrkulacji potrzebuję** — żeby osiągnąć zadany poziom azotanów na odpływie
- **Tryb 2: Co osiągnę przy obecnej recyrkulacji** — predykcja azotanów na wylocie dla aktualnych ustawień (świetne do diagnozy „dlaczego mam za dużo azotu")
- **Tryb 3: Wykres krzywej sprawności** — wizualizacja, gdzie leży granica opłacalności zwiększania recyrkulacji (bo powyżej pewnego punktu pompowanie więcej daje coraz mniej)

---

## Co wyróżnia to narzędzie

**Interpretacja, nie tylko liczba.** Każdy wynik jest oceniany kolorem i komentarzem. SVI = 165? Narzędzie powie „bulking osadu — wykonaj diagnostykę mikroskopową". Recyrkulacja za niska? Podpowie, że koc osadu w osadniku może rosnąć. To różnica między kalkulatorem a doradcą.

**Wzory są jawne.** Każdy kalkulator ma rozwijaną sekcję z dokładnym wzorem (ładnie złożonym matematycznie), wyjaśnieniem każdego symbolu, jednostkami i zakresami referencyjnymi z literatury fachowej. Możesz sprawdzić, skąd się bierze wynik — i nauczyć się przy okazji.

**Historia i eksport.** Zapisujesz wyniki, a potem eksportujesz całą historię do pliku CSV (otwiera się w Excelu) albo JSON. Idealne do śledzenia trendów — np. czy indeks osadu spada z tygodnia na tydzień podczas naprawy procesu.

**Dostępność.** Tryb ciemny i jasny, regulacja wielkości czcionki, oraz czcionka OpenDyslexic dla osób z dysleksją. Bo narzędzie ma być dla każdego.

**Prywatność absolutna.** Zero serwerów, zero kont, zero śledzenia. Otwierasz plik i działa — nawet bez internetu (po pierwszym załadowaniu). Twoje dane procesowe zostają u Ciebie.

---

## Słowniczek skrótów (dla spoza branży)

| Skrót | Co znaczy |
|-------|-----------|
| **Osad czynny** | Zawiesina mikroorganizmów, które „zjadają" zanieczyszczenia ze ścieków |
| **MLSS** | Stężenie tej zawiesiny w reaktorze (gramy na litr) |
| **SVI / DSVI** | Wskaźnik, jak dobrze osad opada — kluczowy dla pracy osadnika |
| **SRT / Wiek osadu** | Średni czas przebywania bakterii w układzie (w dniach) |
| **HRT** | Średni czas przepływu ścieku przez reaktor (w godzinach) |
| **F/M** | Stosunek ilości „pożywienia" do ilości bakterii |
| **BZT₅** | Miara zanieczyszczeń organicznych (ile tlenu zużyją bakterie w 5 dni) |
| **ChZT** | Podobna miara, ale chemiczna i szybsza (minuty zamiast 5 dni) |
| **OWO / TOC** | Bezpośredni pomiar węgla organicznego |
| **Nitryfikacja** | Przemiana amoniaku w azotany przez bakterie |
| **Denitryfikacja** | Usuwanie azotanów (zamiana w gaz azot, który ucieka do atmosfery) |
| **Recyrkulacja** | Zawracanie osadu lub ścieku w obrębie układu |
| **Koagulant (PIX, PAX)** | Środek chemiczny strącający fosfor (sole żelaza lub glinu) |
| **SBR** | Reaktor pracujący porcjami, w cyklach, zamiast w ciągłym przepływie |

---

## Jak zacząć

1. Otwórz plik w przeglądarce (komputer lub telefon).
2. Wybierz moduł z menu po lewej stronie.
3. Wpisz swoje dane — wynik liczy się na bieżąco.
4. Kliknij „Wzór i wyjaśnienie", jeśli chcesz zobaczyć, skąd się bierze.
5. Zapisz wynik do historii, jeśli chcesz śledzić zmiany w czasie.

Wartości wpisane na start to przykładowe liczby — podmień je na swoje.

---

## Ważne zastrzeżenie

Wzory pochodzą z uznanej literatury fachowej (m.in. *Metcalf & Eddy — Wastewater Engineering*, Henze i in. — *Biological Wastewater Treatment*, wytyczne ATV-DVWK). Zakresy referencyjne to wartości literaturowe — w konkretnej oczyszczalni mogą się różnić ze względu na specyfikę ścieków, technologii i pory roku.

**Narzędzie jest pomocą, nie wyrocznią.** Wyniki należy zawsze konfrontować z własnym doświadczeniem, obserwacją procesu i — w razie wątpliwości — z opinią projektanta lub specjalisty. Autor nie ponosi odpowiedzialności za decyzje podjęte na podstawie obliczeń.

---

## Licencja i duch projektu

Narzędzie jest darmowe i otwarte. Używaj, udostępniaj, ucz się, ucz innych. Jeśli komuś pomoże — to cały sens.

Branża wodno-kanalizacyjna trzyma się na ludziach, którzy przez lata zbierali wiedzę „z terenu" i rzadko ją spisywali. To skromna próba, żeby trochę tej wiedzy zebrać w jednym, dostępnym miejscu — zanim odejdzie razem z pokoleniem, które pamięta jeszcze liczenie wieku osadu na kartce w kratkę.

*Jeśli znajdziesz błąd albo masz pomysł na kolejny kalkulator — daj znać. Narzędzie żyje i rośnie.*
