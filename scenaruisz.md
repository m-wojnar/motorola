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

TODO

---

### Slajd 2: Zadanie domowe 5.1

**Opis slajdu**:

- Tytuł: "Zadanie domowe 5.1"
- Treść:
  - Zmień teksturę gracza w zależności od ruchu (twarz w lewo lub w prawo). Podpowiedź: obiekt można odbić lustrzanie przez ustawienie ujemnej skali.

**Narracja**:
"W zadaniu domowym 5.1 będziemy zmieniać teksturę gracza w zależności od kierunku ruchu w grze stworzonej przy użyciu biblioteki PIXI.js. Gdy gracz porusza się w lewo, jego twarz powinna być zwrócona w lewo, a gdy porusza się w prawo, twarz powinna być zwrócona w prawo. Aby to osiągnąć, możemy użyć właściwości skali obiektu, ustawiając ujemną skalę dla odbicia lustrzanego. To zadanie nauczy nas podstaw manipulacji obiektami graficznymi w PIXI.js."

---

### Slajd 3: Zadanie domowe 5.2

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