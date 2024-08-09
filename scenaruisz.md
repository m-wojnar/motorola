# Scenariusz filmiku na YouTube: "Podstawowy kurs języka JavaScript - Część 1"

---

### Slajd 1: Wprowadzenie

**Opis slajdu**:
- Tytuł: "Podstawowy kurs języka JavaScript - Część 1"

**Narracja**:
"Witajcie w pierwszej części kursu JavaScript stworzonego przez fundację TryIT! W tym odcinku nauczymy się podstaw języka JavaScript oraz pracy z Obiektowym Modelem Dokumentu (DOM). Kurs jest przeznaczony dla uczestniczek kursu (TryIT?) oraz wszystkich, którzy chcą nauczyć się JavaScript w ciekawy sposób. Aby w pełni skorzystać z kursu, wymagana jest umiejętność programowania w dowolnym innym języku, w szczególności znajomość podstawowych struktur używanych w programowaniu."

---

### Slajd 2: Spis treści

**Opis slajdu**:
- Tytuł: "Spis treści - Część 1"
- Lista:
  1. Środowisko pracy
  2. Czysty JavaScript
  3. Obiektowy Model Dokumentu

**Narracja**:
"Oto plan naszego pierwszego odcinka. Zaczniemy od przygotowania środowiska pracy, przejdziemy przez podstawy JavaScript, a na końcu zajmiemy się manipulacją DOM. Zaczynajmy!"

---

### Nagranie 1: Nawigacja po kursie

**Opis nagrania**:
- Prezentacja repozytorium i branchów:
  1. Otwórz w przeglądarce repozytorium github z kodem.
  2. Pokaż listę branchy.
  3. Przejdź do pull requests, pokaż przykładowy PR z częścią 1.
  4. Pokaż spis commitów, kliknij przykładowy.
  5. Pokaż PR z zadaniem domowym i jak podejrzeć rozwiązanie sprawdzając wszystkie zmiany.
- Klonowanie repozytorium kursu:
  1. Otwórz terminal lub konsolę.
  2. Wykonaj polecenie: `git clone [link do repozytorium]`.
- Przechodzenie między branchami i commitami:
  1. Aby przejść do odpowiedniego branchu, użyj polecenia: `git checkout [nazwa brancha]`.
  2. Aby zobaczyć historię commitów, użyj polecenia: `git log`.

**Narracja**:
"Zobaczmy, jak poruszać się po kursie. Na początek, otwórzmy w przeglądarce nasze repozytorium z kodem. Po lewej stronie mamy zakładkę "branches". Kliknijmy na nią, aby zobaczyć listę wszystkich dostępnych branchy w repozytorium. Jak widzicie, mamy kilka branchy, które odpowiadają fragmentom kursu i zadaniom domowym. Teraz przejdźmy do zakładki "Pull requests" i wybierzmy PR związany z pierwszą częścią kursu. Widoczny jest spis commitów, które były częścią tego PR. Kliknijmy na jeden z nich, aby zobaczyć zmiany w kodzie dotyczące dane zadania. Teraz znajdźmy PR z zadaniem domowym. Otwierając go, możemy przejrzeć przykładowe rozwiązania zadania domowego w zakładce "Files changed".

Przejdźmy teraz do sklonowania repozytorium kursu. Otwórz terminal lub konsolę na swoim komputerze. Użyjemy polecenia: git clone wraz z linkiem do naszego repozytorium. Pobierze ono całe repozytorium na nasz komputer. Aby przejść do odpowiedniego brancha, użyjemy polecenia: git checkout. Aby zobaczyć historię commitów, które zostały wykonane w repozytorium, użyjemy polecenia: git log. Wyświetli ono listę wszystkich commitów wraz z ich identyfikatorami, autorami i wiadomościami."

---

### Nagranie 2: Instalacja i konfiguracja VS Code oraz Live Server

**Opis nagrania**:
- Krok po kroku instalacja VS Code:
  1. Otwórz stronę Visual Studio Code i pobierz wersję dla swojego systemu operacyjnego.
  2. Zainstaluj VS Code, postępując zgodnie z instrukcjami instalatora.
- Instalacja rozszerzenia Live Server:
  1. Otwórz VS Code.
  2. Przejdź do zakładki "Extensions" (rozszerzenia) po lewej stronie.
  3. Wyszukaj "Live Server" i kliknij "Install".

**Narracja**:
"Przejdźmy teraz do instalacji i konfiguracji naszego środowiska pracy. Zalecamy użycie edytora kodu Visual Studio Code oraz przeglądarki Google Chrome. Dodatkowo, zainstalujemy rozszerzenie Live Server, aby łatwo uruchamiać pliki HTML z poziomu edytora z możliwością automatycznego przeładowania strony po zapisaniu pliku. Otwórz stronę Visual Studio Code i pobierz wersję dla swojego systemu operacyjnego. Po zainstalowaniu, otwórz VS Code i zainstaluj rozszerzenie Live Server."

---

### Nagranie 3: Konsola dewelopera

**Opis nagrania**:
- Otwieranie konsoli dewelopera w przeglądarce Chrome:
  1. Otwórz przeglądarkę Chrome.
  2. Naciśnij klawisz F12 lub kliknij prawym przyciskiem myszy na stronie i wybierz "Zbadaj".
  3. Przejdź do zakładki "Console".

**Narracja**:
"Aby wykonywać proste skrypty JavaScript, będziemy korzystać z konsoli dewelopera w przeglądarce Chrome. Otwieramy ją za pomocą klawisza F12. Konsola pozwala na interaktywne uruchamianie kodu JavaScript."

---

### Slajd 3: Zadanie domowe 1

**Opis slajdu**:
- Tytuł: "Zadanie domowe 1"
- Treść:
  - Przeanalizuj zawartość wybranej strony internetowej (np. tryit.org.pl).

**Narracja**:
"Pierwsze zadanie domowe polega na analizie zawartości wybranej strony internetowej, na przykład tryit.org.pl. Użyj konsoli dewelopera, aby zbadać wybrane elementy strony."

---

### Nagranie 4: Nauka składni JavaScript

**Opis nagrania**:
- Wykonywanie sekwencyjnie wszystkich poleceń z pliku czesc_2.js z równoległym komentarzem.

**Narracja**:
"Teraz przejdziemy przez podstawy programowania w JavaScript, omawiając kluczowe elementy tego języka.

Zaczniemy od najprostszej operacji, jaką jest wypisanie wiadomości do konsoli. Aby to zrobić, używamy funkcji `console.log`, po której umieszczamy tekst, który chcemy wyświetlić. Pamiętaj, aby każdą instrukcję kończyć średnikiem, co jest dobrą praktyką w JavaScript.

Kolejny ważny element to komentarze. Komentarze pozwalają na dodawanie notatek do kodu, które nie są wykonywane przez program. Mamy dwa rodzaje komentarzy: jednolinijkowe, które zaczynają się od dwóch ukośników, oraz wielolinijkowe, które zaczynają się od ukośnika i gwiazdki, a kończą na odwrót.

W JavaScript możemy tworzyć zmienne używając słowa kluczowego `let`. Zmiennym możemy przypisywać różne wartości i wykonywać na nich operacje matematyczne, takie jak dodawanie, odejmowanie, mnożenie, dzielenie, modulo oraz potęgowanie. Następnie mamy operatory porównania, które pozwalają porównywać wartości. Są to między innymi operatory równości, nierówności, większe niż, mniejsze niż oraz porównanie ścisłe. Różnica między podwójnym a potrójnym znakiem równości polega na tym, że potrójny znak równości sprawdza również typ danych. Operatory logiczne, takie jak AND, OR i NOT, pozwalają na tworzenie złożonych warunków logicznych. Są one przydatne w sytuacjach, gdy chcemy sprawdzić więcej niż jeden warunek naraz.

JavaScript jest językiem dynamicznie typowanym, co oznacza, że typ zmiennej jest określany podczas działania programu. Możemy zmieniać typ wartości przypisanej do zmiennej w trakcie działania programu, co daje dużą elastyczność.

Łańcuchy znaków, czyli stringi, możemy tworzyć używając pojedynczych, podwójnych lub specjalnych znaków zwanych backtickami. Backticki pozwalają na tworzenie wielolinijkowych łańcuchów znaków i interpolację zmiennych, co oznacza, że możemy wstawiać wartości zmiennych bezpośrednio do tekstu.

Stałe deklarujemy używając słowa kluczowego `const`. Stałym nie można przypisać nowej wartości po ich zdefiniowaniu, co jest przydatne w sytuacjach, gdy chcemy, aby pewna wartość pozostała niezmienna.

Funkcje w JavaScript można tworzyć na kilka sposobów. W tradycyjna deklaracji funkcji używamy słowa kluczowego `function`, po którym następuje nazwa funkcji, parametry i jej ciało. Możemy również użyć funkcji strzałkowych, które są bardziej zwięzłe i czasami wygodniejsze w użyciu.

Tablice pozwalają na przechowywanie listy wartości. Możemy uzyskać dostęp do elementów tablicy za pomocą indeksów, dodawać nowe elementy na końcu tablicy oraz usuwać ostatnie elementy. Możemy również usuwać dowolne elementy z tablicy za pomocą specjalnej metody.

W JavaScript możemy tworzyć obiekty, które są zbiorami par klucz-wartość, podobnie do słowników w Pythonie. Dostęp do atrybutów obiektu uzyskujemy za pomocą notacji kropkowej lub nawiasów kwadratowych. Możemy dodawać lub modyfikować atrybuty obiektu, a także usuwać je, jeśli są już niepotrzebne.

Instrukcje warunkowe pozwalają na wykonanie kodu w zależności od spełnienia określonych warunków. Możemy używać instrukcji `if-else`, aby sprawdzić różne warunki, a także skróconej wersji instrukcji warunkowej, która jest bardziej zwięzła.

Pętla `for` jest najbardziej popularna i pozwala na iterację przez określoną liczbę kroków lub przejście po całej sekwencji. Możemy również używać pętli `while` i `do-while`, które wykonują kod tak długo, jak długo spełniony jest określony warunek. Możemy przerywać pętle za pomocą instrukcji `break` lub przechodzić do następnej iteracji za pomocą instrukcji `continue`.

Na koniec omówimy klasy w JavaScript. Klasa to definicja struktury danych zawierająca właściwości i metody. Możemy tworzyć obiekty na podstawie klasy, które dziedziczą jej właściwości i metody.
""

---

### Slajd 4: Zadanie domowe 2

**Opis slajdu**:
- Tytuł: "Zadanie domowe 2"
- Treść:
  - Napisz funkcję, której argumentami jest imię i wiek użytkownika.
  - Funkcja powinna zwracać obiekt z imieniem i wiekiem, a także informację o tym, czy użytkownik jest dorosły oraz czy jego wiek jest liczbą parzystą.
  - Utwórz listę z 5 imionami.
  - Napisz pętlę, która przechodzi po wszystkich elementach listy. W każdej iteracji podaj imię użytkownika i wylosuj wiek. Jeśli wiek użytkownika jest parzysty, wypisz jego dane na ekran.
- Podpowiedź:
  - Funkcja, która pozwala wylosować liczbę całkowitą z zadanego przedziału:
    ```
    function getRandomInt(min, max) {
        return Math.floor(Math.random() * (max - min + 1) + min);
    }
    ```

**Narracja:**

"W zadaniu domowym 2 będziemy tworzyć funkcję, która przyjmuje dwa argumenty: imię i wiek użytkownika. Naszym celem jest, aby funkcja zwracała obiekt zawierający imię, wiek, informację o pełnoletniości użytkownika oraz informację o parzystości wieku.

Następnie utworzymy listę z 5 imionami i napiszemy pętlę, która przechodzi po wszystkich elementach tej listy. W każdej iteracji podamy imię użytkownika i wylosujemy jego wiek przy użyciu funkcji `getRandomInt`. Jeśli wiek użytkownika będzie liczbą parzystą, wypiszemy jego dane na ekranie.

Oto funkcja `getRandomInt`, która losuje liczbę całkowitą z zadanego przedziału, co pomoże nam w losowaniu wieku użytkowników."

---

### Slajd 5: Dodatkowe materiały

**Opis slajdu**:
- Tytuł: "Co dalej?"
- Treść:
  - Gdzie szukać informacji?
  - Linki: The Modern JavaScript Tutorial (https://javascript.info), w3schools (https://www.w3schools.com/js)

**Narracja**:
"Chcemy zachęcić Was do dalszego zgłębiania wiedzy na temat JavaScript. W Internecie dostępnych jest wiele zasobów, które mogą wam pomóc w nauce i rozwijaniu umiejętności.

Jednym z najlepszych źródeł informacji jest strona javascript.info, która oferuje szczegółowe i dobrze zorganizowane artykuły na temat JavaScript. Kolejnym wartościowym źródłem jest w3schools.com/js, gdzie znajdziecie mnóstwo praktycznych przykładów i interaktywnych samouczków.

Zachęcamy Was do regularnego odwiedzania dokumentacji, eksperymentowania z kodem i samodzielnego rozwiązywania problemów. Im więcej praktyki, tym lepiej opanujecie JavaScript i zrozumiecie, jak tworzyć dynamiczne i interaktywne strony internetowe."

---

### Slajd 6: Zadanie domowe 3

**Opis slajdu**:
- Tytuł: "Zadanie domowe 3"
- Treść:
  - W dokumentacji znajdź informacje o typach zmiennych w JS.
  - Spróbuj napisać kilka instrukcji warunkowych ze zmiennymi różnych typów.

**Narracja**:
"Trzecie zadanie domowe polega na zapoznaniu się z typami zmiennych w języku JavaScript. Zacznij od przeszukania dokumentacji, aby znaleźć szczegółowe informacje o różnych typach zmiennych, takich jak stringi, liczby, boolean, null czy undefined.

Następnie spróbuj napisać kilka instrukcji warunkowych, w których użyjesz zmiennych różnych typów. Możesz na przykład sprawdzić, czy zmienna jest liczbą, czy stringiem, albo porównać dwie zmienne różnych typów.

To ćwiczenie pomoże ci lepiej zrozumieć, jak działają typy zmiennych w JavaScript oraz jak można je efektywnie wykorzystać w kodzie."

---

### Slajd 7: Obiektowy Model Dokumentu (DOM)

**Opis slajdu**:
- Tytuł: "3. Obiektowy Model Dokumentu (DOM)"
- Treść:
  - Obiektowy model dokumentu (ang. Document Object Model, DOM) – sposób reprezentacji złożonych dokumentów XML i HTML w postaci modelu obiektowego. 
- Ilustracja: 
  - Dduże drzewo z rozgałęzieniami. Na samej górze drzewa znajduje się prostokąt oznaczony jako document lub HTML. Bezpośrednio pod nim, jako dzieci, są dwa prostokąty oznaczone jako `head` i `body`. Pod `head` mogą być pokazane przykładowe dzieci, takie jak `title` czy `meta`. Pod `body` narysowane są różne węzły reprezentujące typowe elementy HTML, takie jak `h1`, `p`, `div`. Na przykład, `ul` może mieć pod sobą kilka `li`, co ilustruje pojęcie dzieci w węzłach DOM. Każdy węzeł może być przedstawiony jako prostokąt w rónych kolorach w zaleności od typu.
  - Jeśli się zmieści, to wynikowa strona HTML odpowiadająca temu drzewu DOM, ewentualnie strzałki pomiędzy wybranymi węzłami i elementami strony.

**Narracja**:
"Document Object Model, w skrócie DOM, jest hierarchiczną strukturą danych, która reprezentuje stronę HTML jako zestaw połączonych ze sobą obiektów. Możemy myśleć o DOM jak o drzewie, gdzie każdy element strony jest węzłem tego drzewa. Węzły mogą mieć dzieci, które są innymi węzłami. Na przykład, element `ul` może mieć dzieci w postaci elementów `li`.

Dzięki tej strukturze drzewa, skrypty, takie jak JavaScript, mogą dynamicznie manipulować treścią, strukturą i stylami strony internetowej. Możemy używać JavaScriptu do zmiany tekstu nagłówka, dodawania nowych elementów do strony, czy też modyfikacji atrybutów istniejących elementów. DOM umożliwia łatwy dostęp do każdej części dokumentu poprzez nawigację po węzłach drzewa. Dzięki temu możemy tworzyć interaktywne i dynamiczne strony internetowe."

---

### Nagranie 5: Selekcja i manipulacja elementami DOM

**Opis nagrania**:
- Otworzenie strony z VS Code i Live Server.
- Wykonywanie sekwencyjnie wszystkich poleceń z pliku czesc_3.html z równoległym komentarzem. 
- Po każdym fragmencie przeładowanie strony i pokazanie oczekiwanego efektu.

**Narracja**:
"Zaczynamy od struktury dokumentu HTML. W naszym przykładzie definiujemy styl dla całej strony, używając selektora body i klasy `container` oraz `box`. Te style określają wygląd elementów, takie jak czcionka, układ oraz kolory. W sekcji `body` mamy dwa główne elementy `div` z klasą `box`. Jeden z nich ma identyfikator `click`, a drugi `list`. Element `click` wyświetla tekst 'Kliknij!', a element list zawiera ukrytą listę punktowaną, która stanie się widoczna po pewnych operacjach. Otwórzmy plik w VS Code i użyjmy Live Server, aby na żywo obserwować zmiany na stronie. Po każdym zapisie pliku, strona zostanie przeładowana i od razu zobaczymy wprowadzone zmiany.

Teraz przejdźmy do wstawienia JavaScript do strony HTML. Skrypty JavaScript umieszczamy wewnątrz znaczników script. Zobaczmy teraz kilka przykładów, które pokazują różne sposoby użycia JavaScript do manipulacji stroną.

Pierwszy przykład pokazuje, jak wyświetlić wiadomość użytkownikowi. Używamy funkcji `alert`, `prompt` oraz `confirm`, aby wyświetlić okno dialogowe, zapytać użytkownika o imię i sprawdzić, czy jest pewien swojego wyboru. Te komunikaty są przydatne do interakcji z użytkownikiem bezpośrednio z poziomu strony.

W kolejnym przykładzie pokazujemy, jak uzyskać dostęp do elementu DOM i zmienić jego styl. Warto zwrócić uwagę na funkcję `document.querySelector`, która pozwala na uzyskanie uchwytu do odpowiedniego elementu DOM. W naszym przypadku będzie to element o identyfikatorze `click`, dlatego uzyjemy selektora `#click`. Można również uzyskiwać dostęp do obiektów wyszukując po klasie lub strukturze, po więcej szczegółów odsyłamy Was do dokumentacji funkcji `querySelector`. Za pomocą funkcji `setTimeout` ustalamy opóźnione wywołanie wewnętrznej strzałkowej funkcji i zmieniamy kolor tła elementu `click` po trzech sekundach.

Za pomocą funkcji `addEventListener` możemy nasłuchiwać na kliknięcia na elemencie `click`. Każde kliknięcie wywołuje funkcję, która zwiększa wartość zmiennej `score` i aktualizuje tekst wewnątrz elementu.

Zobaczmy również utworzyć nowy element DOM i go usunąć. Tworzymy nowy element `div` za pomocą `document.createElement` i nadajemy mu tekst "Dodatkowa wiadomość" używając `textContent`. Aby wyróżnić ten nowy element, zmieniamy jego kolor tekstu na czerwony, przypisując odpowiednią wartość do stylu `color`. Ten nowo utworzony element dodajemy jako dziecko do elementu `box` za pomocą metody `appendChild`. Dzięki temu nowy element staje się widoczny na stronie wewnątrz elementu `click`. Ponownie używamy `setTimeout`, tym razem aby po dwóch sekundach od dodania elementu usunąć go. Robimy to, wywołując metodę `removeChild` na `box`. W ten sposób, po upływie określonego czasu, element ten zostaje usunięty ze strony.

Przejdźmy teraz do modyfikacji listy. Używając `setInterval`, a więc metody, która pozwala na wywoływanie funkcji w określonych odstępach czasu, zmieniamy tekst każdego elementu listy co sekundę. Zmieniamy również widoczność elementów `click` i `list`, aby zarządzać widocznością elementów na stronie.

Ostatni przykład to zadanie domowe, które polega na implementacji logiki zmieniającej kolor tła elementu click na zielony lub czerwony w zależności od wyniku, który jest parzysty lub nieparzysty. Za pomocą addEventListener i prostych warunków, możemy tworzyć dynamiczne i interaktywne strony."

---

### Slajd 8: Zadanie domowe 4

**Opis slajdu**:
- Tytuł: "Zadanie domowe 4"
- Treść:
  - Zmień kolor pudełka na jasnozielony, jeśli liczba kliknięć jest parzysta.
  - Zmień kolor na czerwony, jeśli liczba kliknięć jest nieparzysta.

**Narracja**:
"Czwarte zadanie domowe polega na manipulacji elementami HTML przy użyciu JavaScriptu. Twoim zadaniem jest stworzenie prostego interaktywnego pudełka, którego kolor zmienia się w zależności od liczby kliknięć.

Wykorzystaj element `div` o klasie `boz`. Następnie w JavaScript napisz funkcję, która będzie zliczać kliknięcia na pudełko. W zależności od tego, czy liczba kliknięć jest parzysta czy nieparzysta, zmień kolor pudełka odpowiednio na jasnozielony lub czerwony. Przydadzą się używane przed chwilą funkcje, m.in. `addEventListener`."

---

### Slajd 9: Zakończenie

**Opis slajdu**:
- Tytuł: "Koniec części 1"

**Narracja**:
"To już koniec części 1 tego kursu. Nie zapomnijcie obejrzeć drugiej części naszego kursu, gdzie stworzymy własną grę w przeglądarce za pomocą JavaScript!"

---

# Scenariusz filmiku na YouTube: "Podstawowy kurs języka JavaScript - Część 2"

---

### Slajd 1:

**Opis slajdu**:
- Tytuł: "Podstawowy kurs języka JavaScript - Część 2"

**Narracja**:
"Witajcie w drugiej części kursu JavaScript stworzonego przez fundację TryIT! W tym odcinku nauczymy stworzymy własną grę w przeglądarce za pomocą JavaScript! Jeśli nie oglądałaś jeszcze pierwszej częście tego kursu, sugerujemy obejrzenie jej w pierwszej kolejności, jeszcze przed przystąpieniem do implementacji gry."

---

### Nagranie 1: PixiJS

**Opis nagrania**:
- Poruszanie się po dokumentacji biblioteki PixiJS (https://pixijs.com i https://pixijs.com/8.x/guides)
- Pokazanie prostych przykładów gier z dokumentacji (https://pixijs.com/8.x/playground)

**Narracja**:
"W tym nagraniu przyjrzymy się bibliotece PixiJS, która jest potężnym narzędziem do tworzenia gier i aplikacji graficznych w JavaScript. Zacznijmy od odwiedzenia dokumentacji PixiJS, dostępnej pod adresem `pixijs.com` oraz `pixijs.com/8.x/guides`. Dokumentacja jest świetnym źródłem informacji, które pomogą Wam zrozumieć podstawowe oraz zaawansowane funkcje PixiJS.

W sekcji 'Guides' znajdziecie szczegółowe przewodniki, które krok po kroku wprowadzą Was w różne aspekty używania PixiJS, takie jak tworzenie scen, zarządzanie obiektami graficznymi czy obsługa zdarzeń. Każdy przewodnik jest dobrze opisany i ilustrowany, co ułatwia naukę i implementację.

Następnie, odwiedźmy stronę z przykładami gier, która znajduje się pod adresem pixijs.com/8.x/playground. Na tej stronie znajdziecie różne przykłady zastosowań PixiJS, które możecie przetestować na żywo. Przykłady te pokazują, jak tworzyć proste gry i efekty graficzne, co może być doskonałym punktem wyjścia dla własnych projektów.

Zapraszam Was do eksploracji dokumentacji oraz przykładów i zachęcam do zabawy z PixiJS. Praktyka z rzeczywistymi przykładami pomoże Wam lepiej zrozumieć jak korzystać z tej biblioteki i przyspieszy Waszą naukę tworzenia dynamicznych i interaktywnych aplikacji graficznych."

---

### Nagranie 2a: Tworzenie gry od początku do końca

**Opis nagrania**:
- Implementacja gry krok po kroku, a w wyznaczonych momentach zaprezentowanie obecnego stanu gry w przeglądarce (uruchomiona w tle w Live Server). Fragmenty pomiędzy prezentacjami stanu gry odpowiadają kolejnym commitom na branchu `gra`.

**Narracja**:
"Wszystkie materiały niezbędne w trakcie budowy gry znajdziecie na branchu `materialy`, dlatego przed rozpoczęciem implementacji, warto przełączyć się na ten branch.

Zacznijmy od stworzenia szkieletu naszej gry 'Łapacz jabłek'. Pierwszym krokiem jest przygotowanie strony HTML, która będzie bazą dla naszej gry. Ustawmy kodowanie znaków, tytuł strony i styl naszej strony. Ustawiamy marginesy html i body na 0px, co usuwa domyślne odstępy wokół treści. Następnie, dla obu tych elementów, ustawiamy wysokość na 99.5%, co sprawia, że strona zajmuje praktycznie całą wysokość przeglądarki.

[PREZENTACJA STANU GRY]

Teraz, gdy mamy gotowy podstawowy szkielet naszej strony HTML, możemy przejść do integracji z biblioteką PixiJS, która będzie podstawą dla naszej gry. Zaczynamy od dodania skryptu, który pobiera bibliotekę PixiJS bezpośrednio z jej oficjalnego źródła. W sekcji `script`, wskazujemy na wersję 8.2.0 tej biblioteki. Następnie dodajemy kolejny skrypt, tym razem z biblioteki Pixi Sound. Jest to rozszerzenie PixiJS, które pozwala nam na łatwe dodawanie dźwięków do gry. Pobieramy ją z repozytorium na GitHubie i wskazujemy na wersję 6.0.0. Dźwięki w grze to bardzo ważny element, który zwiększa immersję i sprawia, że rozgrywka staje się bardziej angażująca.

Po zaimportowaniu tych bibliotek, tworzymy kolejny blok `script`, w którym ustawiamy `type` na `module`. Na razie zostawiamy ten blok pusty, ale to właśnie tutaj będziemy pisać kod, który będzie odpowiedzialny za całą logikę naszej gry. W kolejnych krokach zaczniemy implementować poszczególne funkcje i elementy, które sprawią, że nasza gra ożyje na ekranie.

Utworzymy instancję aplikacji PixiJS, która będzie podstawowym narzędziem do renderowania grafiki na naszej stronie. Aby to zrobić, wywołujemy konstruktor `PIXI.Application`, co tworzy nową aplikację PixiJS. 

Kolejnym krokiem jest inicjalizacja tej aplikacji przy użyciu metody `init`. Przekazujemy konfigurację naszej aplikacji. Po pierwsze, ustawiamy `autoDensity`, co sprawia, że PixiJS automatycznie dostosuje rozdzielczość renderowania w zależności od urządzenia, na którym gra jest uruchamiana. Dalej, konfigurujemy aplikację, aby jej rozmiar był automatycznie dopasowany do rozmiaru okna przeglądarki. Ustawiamy opcję `resizeTo` na document.body, co oznacza, że nasza gra zawsze będzie wypełniać całe dostępne okno przeglądarki. Na koniec, dodajemy aplikację do strony HTML. Robimy to, dołączając płótno (`canvas`), na którym PixiJS będzie rysować naszą grę, bezpośrednio do elementu body strony. Używamy do tego metody `appendChild`, która wstawia płótno PixiJS jako ostatni element w `body`.

[PREZENTACJA STANU GRY]

W tym etapie zajmiemy się dodaniem głównego bohatera naszej gry, czyli postaci gracza, na ekran. Rozpoczynamy od załadowania tekstury dla gracza, czyli obrazu, który będzie reprezentował postać. Używamy do tego funkcji `PIXI.Assets.load`, która wczytuje grafikę z pliku o nazwie `gracz.png`. Po załadowaniu, ustawiamy tryb skalowania tej tekstury na `nearest`, co zapewnia, że podczas powiększania lub pomniejszania obraz zachowa ostre krawędzie, zamiast być rozmyty.

Kiedy tekstura jest już gotowa, tworzymy na jej podstawie obiekt gracza przy użyciu `PIXI.Sprite.from`. Obiekty `Sprite` to podstawowe elementy graficzne w PixiJS, które możemy dowolnie pozycjonować, skalować i animować na scenie.

Kolejnym krokiem jest ustawienie pozycji gracza na ekranie. Umieszczamy go na środku szerokości ekranu, co osiągamy, dzieląc szerokość płótna przez dwa i przypisując tę wartość do współrzędnej x gracza. Następnie ustawiamy gracza tuż nad dolną krawędzią ekranu, odejmując wysokość jego postaci i 10 pikseli marginesu od wysokości płótna i przypisując to do współrzędnej y.

Dostosowujemy skalę gracza, aby był dobrze widoczny na ekranie. Używamy do tego metody `scale.set`, aby powiększyć jego rozmiar trzykrotnie w obu kierunkach - zarówno poziomym, jak i pionowym. Dzięki temu postać będzie wystarczająco duża, aby była łatwo rozpoznawalna podczas rozgrywki.

Ustawiamy także punkt obrotu gracza na środek jego postaci, używając metody `anchor.set(0.5)`. Dzięki temu wszelkie obracanie i skalowanie postaci będzie odbywać się względem jej środka, co jest szczególnie istotne w przypadku animacji i interakcji z obiektami w grze.

Na końcu, dodajemy postać gracza do sceny gry za pomocą `app.stage.addChild(player)`. W ten sposób nasz bohater pojawia się na ekranie i jest gotowy do dalszych interakcji w grze.

[PREZENTACJA STANU GRY]

---

### Slajd 2: Prawa autorskie

**Opis slajdu**:

- Tytuł: "Prawa autorskie w tworzeniu gier i aplikacji"
- Treść:
  - Logotypy licencji?

**Narracja**:
"Przy tworzeniu gier i aplikacji, ważne jest, aby pamiętać o przestrzeganiu praw autorskich oraz licencji dotyczących używanych materiałów. Korzystanie z cudzych zasobów, takich jak grafiki, dźwięki czy tekstury, wymaga przestrzegania licencji, które mogą określać sposób, w jaki można używać, modyfikować i udostępniać te materiały.

Warto zwrócić uwagę na otwarte licencje, które mogą ułatwić proces twórczy. Jednym z przykładów jest licencja Creative Commons Zero (CC0). Licencja ta pozwala na korzystanie z materiałów w sposób całkowicie wolny – możesz je używać, modyfikować i rozpowszechniać bez obaw o naruszenie praw autorskich. Jest to szczególnie przydatne dla twórców gier i aplikacji, którzy szukają darmowych zasobów, które mogą legalnie wykorzystać w swoich projektach.

Istnieje wiele serwisów internetowych, które oferują materiały objęte licencjami typu CC0 oraz innymi otwartymi licencjami. Jednym z takich serwisów jest OpenGameArt. Na tej stronie znajdziesz bogaty zbiór darmowych grafik, dźwięków i innych zasobów, które możesz wykorzystać w swoich projektach, oszczędzając czas i środki, a także unikając problemów związanych z licencjami. Materiały uyzywane w tej grze pochodzą właśnie z tej strony i są wykorzystywane na licencji CC0.

Pamiętaj, aby zawsze sprawdzać warunki licencji i respektować prawa twórców. Korzystając z materiałów zgodnie z ich licencjami, wspierasz kreatywność w społeczności i zapewniasz sobie spokój, że Twoje projekty są zgodne z prawem."

---

### Nagranie 2b: Tworzenie gry od początku do końca [kontynuacja]

**Opis nagrania**:
- Implementacja gry krok po kroku, a w wyznaczonych momentach zaprezentowanie obecnego stanu gry w przeglądarce (uruchomiona w tle w Live Server). Fragmenty pomiędzy prezentacjami stanu gry odpowiadają kolejnym commitom na branchu `gra`.

**Narracja**:
"Dodajmy teraz tło, analogicznie do tekstury gracza: ładujemy tło i ustawiamy tryb skalowania, a następnie tworzymy obiekt `Sprite`. Następnie, aby tło idealnie wypełniało cały obszar gry, ustawiamy jego szerokość na szerokość płótna, czyli okna przeglądarki, oraz wysokość na pełną wysokość ekranu. Dodajemy tło do sceny gry.

[PREZENTACJA STANU GRY]

W tej części naszej gry zajmiemy się dodaniem podstawowego sterowania postacią gracza. Zaczynamy od ustawienia początkowej prędkości gracza na wartość zero, co oznacza, że na początku gry postać nie porusza się w żadnym kierunku.

Aby umożliwić graczowi kontrolowanie postaci, dodajemy nasłuch na zdarzenia klawiatury, które będą reagować na naciśnięcia i puszczenie klawiszy strzałek. Pierwszy nasłuch to `keydown`, który uruchamia się w momencie wciśnięcia klawisza. Jeżeli gracz naciśnie strzałkę w lewo, prędkość gracza zostaje ustawiona na wartość ujemną, co spowoduje, że postać zacznie poruszać się w lewo. Analogicznie, jeżeli gracz naciśnie strzałkę w prawo, prędkość zostanie ustawiona na wartość dodatnią, co sprawi, że postać będzie poruszać się w prawo.

Kolejny nasłuch, `keyup`, działa wtedy, gdy gracz przestaje naciskać klawisz. Jeśli gracz puści strzałkę w lewo lub w prawo, prędkość gracza zostanie zresetowana do zera, co zatrzyma ruch postaci.

Aby zapewnić płynność ruchu, używamy mechanizmu `app.ticker`, który uruchamia się w każdej klatce animacji. W każdej klatce aktualizujemy pozycję gracza, dodając do jego współrzędnej poziomej wartość jego prędkości. Dzięki temu gracz porusza się w zadanym kierunku z odpowiednią prędkością.

Na koniec, aby zapobiec sytuacji, w której postać gracza wychodzi poza ekran, dodajemy ograniczenie. Zastosowaliśmy funkcje `Math.max` i `Math.min`, które kontrolują, czy postać nie przekroczyła granic ekranu. Jeśli gracz zbliży się do lewej lub prawej krawędzi, jego pozycja zostanie odpowiednio skorygowana, aby nie wyszedł poza widoczny obszar gry.

[PREZENTACJA STANU GRY]

Wprowadzimy mechanizmu generowania spadających jabłek, które gracz będzie musiał złapać. Podobnie jak poprzednio, ładujemy teksturę obiektu. Następnie tworzymy tablicę `objects`, która będzie przechowywać wszystkie aktualnie spadające obiekty w grze. 

Główna część kodu to funkcja `spawnObject`, która odpowiada za tworzenie nowych spadających obiektów. Na początku w tej funkcji tworzymy nowy obiekt typu `Sprite` na bazie załadowanej wcześniej tekstury. Ustawiamy jego początkową pozycję poziomą na losową wartość w obrębie szerokości ekranu, ale tak, aby nie wykraczał on poza granice. Pozycja pionowa jest ustawiona tuż nad górną krawędzią ekranu.

Prędkość pionowa (`vy`) jest ustalona na wartość 1, co oznacza, że obiekt będzie się poruszał w dół ze stałą prędkością. Dodatkowo obiekt jest skalowany, aby był nieco większy niż jego pierwotny rozmiar.

Następnie dodajemy ten nowo utworzony obiekt do sceny oraz do tablicy `objects`, dzięki czemu będziemy mogli zarządzać jego ruchem oraz interakcjami w kolejnych krokach. Ostatnim elementem jest wywołanie funkcji `spawnObject`, która inicjuje cały proces. Funkcja ta będzie wywoływać samą siebie z określoną częstotliwością co 3 sekundy.

[PREZENTACJA STANU GRY]

W tej chwili jabłka jeszcze nie spadają z góry ekranu, dlatego w tym momencie skupimy się na aktualizowaniu pozycji spadających obiektów. Najpierw dodajemy funkcję, która będzie regularnie wywoływana, dzięki mechanizmowi `ticker` wbudowanemu w PixiJS. Funkcja ta jest kluczowa, ponieważ umożliwia nam aktualizowanie stanu gry w każdym klatce animacji.

Główna część funkcji to pętla, która przechodzi przez każdy obiekty w tablicy `objects`. Dla każdego z tych obiektów zwiększamy jego współrzędną pionową y o wartość `vy`, co sprawia, że obiekt przesuwa się w dół ekranu z ustaloną wcześniej prędkością.

Kolejnym krokiem jest sprawdzenie, czy obiekt nie wyszedł poza dolną krawędź ekranu. Jeśli tak się stanie, obiekt zostaje usunięty zarówno ze sceny, jak i z tablicy objects. Wykorzystujemy do tego metodę `getBounds()`, która zwraca aktualne granice obiektu. Sprawdzamy, czy dolna krawędź obiektu (`maxY`) znajduje się poniżej wysokości ekranu. Jeśli tak, obiekt jest usuwany ze sceny za pomocą removeChild, a następnie aktualizujemy tablicę objects, usuwając z niej referencję do tego obiektu.

Ten proces jest kluczowy dla optymalizacji gry, ponieważ zapobiega nadmiernemu obciążeniu pamięci poprzez usuwanie obiektów, które nie są już widoczne i nie mają wpływu na rozgrywkę. Tak zaprojektowana funkcjonalność zapewnia ciągły ruch obiektów w dół ekranu, tworząc dynamiczne środowisko gry.

[PREZENTACJA STANU GRY]

Zaimplementujemy teraz funkcję odpowiedzialną za wykrywanie kolizji między graczem, a spadającymi obiektami. Tworzymy funkcję `hitTestRectangle`, która przyjmuje dwa argumenty: gracza oraz obiekt. Wewnątrz tej funkcji najpierw pobieramy granice obu elementów na ekranie, czyli obszary, w których się one znajdują. Granice te są reprezentowane przez współrzędne krawędzi prostokątów otaczających te elementy.

Następnie sprawdzamy, czy obiekt znajduje się całkowicie nad lub pod graczem, poprzez porównanie współrzędnych pionowych ich granic. Jeśli obiekt nie nakłada się na gracza w pionie, zwracamy wartość `false`, co oznacza brak kolizji.

Jeśli jednak obiekt znajduje się na tej samej wysokości co gracz, przechodzimy do sprawdzenia współrzędnych poziomych. Jeśli granice obiektu i gracza przecinają się w poziomie, mamy do czynienia z kolizją, a funkcja zwraca `true`.

Następnie, w funkcji odpowiedzialnej za aktualizację pozycji obiektów, dodajemy dodatkową logikę do wykrywania kolizji. Dla każdego obiektu, który spada w dół, najpierw aktualizujemy jego pozycję. Następnie, używając funkcji `hitTestRectangle`, sprawdzamy, czy obiekt zderzył się z graczem. Jeśli kolizja zostanie wykryta, natychmiast usuwamy obiekt ze sceny oraz z tablicy `objects`.

[PREZENTACJA STANU GRY]

Teraz dodajemy istotne elementy zarządzające wynikami, życiami oraz końcem gry, a także wprowadzimy tekst informacyjny na ekranie.

Tworzymy trzy elementy tekstowe przy użyciu PIXI. Pierwszy z nich to tekst wyniku, który wyświetla aktualny wynik w lewym górnym rogu ekranu. Drugi to tekst liczby żyć, który umieszczamy w prawym górnym rogu. Ostatni element to główny tekst, który będzie wyświetlał komunikaty końcowe i umieszczamy go w centrum ekranu.

Te teksty są aktualizowane dynamicznie w trakcie gry. Zacznijmy od dodania logiki do zwiększania wyniku. W momencie, gdy wykryjemy kolizję między graczem a obiektem, dodajemy do wyniku 10 punktów. Tekst wyświetlający wynik jest aktualizowany, aby odzwierciedlić nową wartość punktacji. To sprawia, że gra staje się bardziej dynamiczna i nagradza gracza za udane interakcje. Jeśli obiekt spadnie poza ekran, zmniejszamy liczbę żyć gracza o 1 i aktualizujemy tekst wyświetlający liczbę pozostałych żyć. Kiedy liczba żyć spadnie do 0, oznacza to koniec gry. Wtedy wyświetlamy na środku ekranu komunikat 'Koniec gry!', wyśrodkowując tekst zarówno w pionie, jak i w poziomie. Zatrzymujemy animację i zatrzymujemy generator obiektów, aby uniknąć dalszego tworzenia nowych przeszkód. 

[PREZENTACJA STANU GRY]

Teraz dodajemy elementy dźwiękowe, które wzbogacą naszą grę i uczynią ją bardziej angażującą.

Zaczynamy od załadowania dźwięków, które będą odtwarzane w różnych sytuacjach w grze. Używamy funkcji `PIXI.sound.add` do dodania trzech różnych dźwięków. Pierwszy z nich to dźwięk przechwycenia obiektu. Drugi to dźwięk upadku obiektu, a ostatni to dźwięk końca gry.

[PREZENTACJA STANU GRY]

Teraz dodalamy parametry do naszej gry, które kontrolują różne aspekty jej rozgrywki oraz wprowadzimy mechanizm zwiększania trudności w trakcie gry.

Najpierw definiujemy kilka podstawowych parametrów gry, które będą kontrolować prędkość gracza, prędkość obiektów, ilość punktów za złapanie obiektu, częstotliwość generowania obiektów oraz odpowiadające maksymalne lub minimalne wartości.

Zmieniamy sposób ustawiania prędkości gracza. Poprzednio przypisywaliśmy prędkość bezpośrednio w obsłudze zdarzeń klawiatury, teraz dostosowujemy prędkość gracza do zdefiniowanego parametru `playerSpeed`, co pozwala na łatwiejszą modyfikację i dostosowanie prędkości gracza.

W funkcji generowania obiektów `spawnObject`, dodajemy losowe wartości do prędkości obiektów, co sprawia, że każda instancja obiektu może mieć inną prędkość, co zwiększa dynamikę gry. Zmieniamy również częstotliwość generowania obiektów z 3000 milisekund na wartość określoną przez `objectSpawnRate`.

Wprowadzamy teraz mechanizm zwiększania trudności, który jest uruchamiany co 5 sekund. W funkcji `updateDifficulty` stopniowo zwiększamy prędkość gracza, aż do wartości określonej przez `maxPlayerSpeed`, a także analogicznie zwiększamy prędkość obiektów oraz liczbę punktów zdobywanych za złapanie obiektów. Dodatkowo zmniejszamy `objectSpawnRate`, co oznacza, że obiekty będą generowane coraz szybciej, ale nie szybciej niż określona minimalna wartość `objectMinSpawnRate`.

Podczas aktualizacji pozycji obiektów dodaliśmy możliwość zwiększania wyniku o wartość `objectScore` za każdy złapany obiekt. Po zakończeniu gry, zatrzymujemy również zwiększanie trudności rozgrywki.

[PREZENTACJA STANU GRY]

Gratulacje! Ukończyliśmy właśnie implementację naszej gry! Teraz masz w pełni funkcjonalną grę, w której zaimplementowaliśmy sterowanie graczem, łapanie spadających obiektów i radzenie sobie z rosnącą trudnością.

Ale to nie koniec! Aby dalej rozwijać swoje umiejętności i uczynić grę bardziej atrakcyjną, zachęcamy do wykonania zadań domowych, które będą przedstawione za chwilę. Ćwicząc je, będziesz mógła dodać nowe funkcje, poprawić istniejące mechanizmy i udoskonalić swoją grę. To doskonała okazja, aby eksperymentować i nauczyć się jeszcze więcej o programowaniu gier w JavaScript.

Życzymy powodzenia i świetnej zabawy przy rozbudowie gry!"

---

### Slajd 3: Zadanie domowe 5.1

**Opis slajdu**:

- Tytuł: "Zadanie domowe 5.1"
- Treść:
  - Zmień teksturę gracza w zależności od ruchu (twarz w lewo lub w prawo). Podpowiedź: obiekt można odbić lustrzanie przez ustawienie ujemnej skali.

**Narracja**:
"W zadaniu domowym 5.1 będziemy zmieniać teksturę gracza w zależności od kierunku ruchu w grze stworzonej przy użyciu biblioteki PIXI.js. Gdy gracz porusza się w lewo, jego twarz powinna być zwrócona w lewo, a gdy porusza się w prawo, twarz powinna być zwrócona w prawo. Aby to osiągnąć, możemy użyć właściwości skali obiektu, ustawiając ujemną skalę dla odbicia lustrzanego. To zadanie nauczy nas podstaw manipulacji obiektami graficznymi w PIXI.js."

---

### Slajd 4: Zadanie domowe 5.2

**Opis slajdu**:

- Tytuł: "Zadanie domowe 5.2"
- Treść:
  - Dodaj wiatr - spraw, aby jabłka spadały krzywo (pamiętaj, że jabłka nie mogą wyjść poza ekran!)

**Narracja**:
"W zadaniu domowym 5.2 dodamy element wiatru do naszej gry. Sprawimy, że jabłka będą spadały krzywo zamiast pionowo w dół, co doda dynamiki do rozgrywki. Ważne jest, aby jabłka nie wychodziły poza ekran, więc będziemy musieli dostosować ich trajektorię spadania. Istotne jest tutaj stworzenie odpowiednich instrukcji warunkowych oraz wykrywanie zetknięcia z krawędzią ekranu."

---

### Slajd 5: Zadanie domowe 5.3

**Opis slajdu**:

- Tytuł: "Zadanie domowe 5.3"
- Treść:
  - Dodaj restart (naciśnij spację na początku i po zakończeniu gry).

**Narracja**:
"Dodamy teraz funkcjonalność restartu gry. Użytkownik będzie mógł nacisnąć spację, aby rozpocząć grę od nowa zarówno na początku, jak i po jej zakończeniu. Wykorzystaj wiedzę na temat obsługi zdarzenń klawiatury i spróbuj resetować stan gry, aby umożliwić jej ponowne uruchomienie."

---

### Slajd 6: Zadanie domowe 5.4

**Opis slajdu**:

- Tytuł: "Zadanie domowe 5.4"
- Treść:
  - Dodaj tablicę wyników (pokaż 3 najlepsze wyniki na ekranie końca gry).

**Narracja**:
"Kontynuując poprzednie zadanie, w zadaniu 5.4 dodamy tablicę wyników do naszej gry. Na ekranie końca gry wyświetlimy trzy najlepsze wyniki, które gracze osiągnęli. Dzięki temu nasza gra stanie się bardziej angażująca i konkurencyjna."

---

### Slajd 7: Zakończenie

**Opis slajdu**:
- Tytuł: "Koniec części 2"

**Narracja**:
"Dotarliśmy w tym momencie do końca całego kursu. Mamy nadzieję, że był on pomocny, a jednocześnie zapraszamy Was do dalszej nauki i eksperymentowania z JavaScript!"

---