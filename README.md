# Podstawowy kurs języka JavaScript

Tutaj opis kursu, dla kogo jest skierowany, jakie są wymagania wstępne, co uczestnik kursu będzie umiał po jego ukończeniu. TODO: Zamieścić link do filmiku.

## Spis treści

1. [Środowisko pracy](#1-środowisko-pracy)
2. [Czysty JavaScript](#2-czysty-javascript)
3. [Obiektowy Model Dokumentu](#3-obiektowy-model-dokumentu)
4. [Gra w Łapanie Jabłek](#4-gra-w-łapanie-jabłek)
5. [Podsumowanie](#5-podsumowanie)
   
## 1. Środowisko pracy

### Edytor kodu

Zalecanym edytorem kodu do realizacji zadań w kursie jest VS Code. Można go pobrać ze strony [Visual Studio Code](https://code.visualstudio.com/). Wspiera wszystkie popularne systemy operacyjne (Windows, Linux, MacOS).

### Rozszerzenie "Live Server"

Aby uruchamiać pliki HTML z kodem JavaScript w przeglądarce, należy zainstalować rozszerzenie "Live Server", które umożliwia automatyczne przeładowywanie strony po zapisaniu zmian w pliku. W tym celu, należy:
- uruchomić VS Code
- przejść do zakładki *Extensions* i wyszukać rozszerzenie "Live Server"
- Zainstalować rozszerzenie

### Nawigacja po kursie 

Kurs składa się z kilku części (patrz [spis treści](#spis-treści)), każda z nich jest na wydzielonym branchu wraz z utworzonym Pull Requestem. Dodatkowo, części podzielone są na zadania reprezentowane przez commity danej części kursu. W trakcji realizacji kurs, kursant powinien przechodzić przez poszczególne branche i commity, aby ostatecznie zrealizować wszystkie zadania. Kurs nie ma na celu nauki systemów wersjonowania kodu, jednak dla wygody kursantów, przedstawiamy potrzebne komendy do nawigacji po kursie:

Pierwszym krokiem jest sklonowanie repozutorium z kursem na lokalny komputer. W tym celu, należy wykonać komndę:
```bash
git clone https://github.com/m-wojnar/motorola.git
cd motorola
```

Po sklonowaniu repozytorium znajdujemy się na branchu `main`, czyli głównym branchu repozytorium. Aby przejść do konkretnej części kursu, reprezentowanej przez oddzielny branch, należy wykonać komendę:
```bash
git checkout -t origin/nazwa_brancha    # jeżeli przechodzimy na dany branch po raz pierwszy
git checkout nazwa_brancha              # jeżeli przechodzimy na dany branch po raz kolejny
```

Po przejściu na odpowiedni branch, możemy sprawdzić listę commitów, które reprezentują zadania do wykonania w danej części kursu. W tym celu, należy wykonać komendę:
```bash
git log
```

Każdy commit odpowiada konkretnemu zadaniu. Aby poruszać się między commitami (zadaniami) w obrębie danego brancha (części kursu), należy wykonać komendę:
```bash
git checkout id_commitu
```

## 2. Czysty JavaScript

Pierwsza właściwa część kursu ma na celu zapoznać kursanta ze składnią języka JavaScript, podstawowymi instrukcjami oraz obsługi konsoli dewelopera JS w przeglądarce. Aby przejść do tej części kursu, należy wykonać komendę:
```bash
git checkout -t origin/czesc-2

# lub, jeżeli branch został wcześniej pobrany na lokalne repozytorium:
git checkout czesc-2
```

### Konsola dewelopera

Aby wykonywać proste skrypty JS, zalecamy korzystanie z konsoli dewelopera w przeglądarce. Aby otowrzyć konsolę dewelopera w polecanej przeglądarce Chrome, można użyć klawisza `F12`. Taka konsola, oprócz wyświetlania komunikatów i błędów, pozwala na interaktywne uruchamianie kodu JS (aby umożliwić wklejanie kodu do konsoli, należy zaznaczyć opcję `alow pasting`).

#### **Zadanie domowe 1**

Przeanalizuj zawartość wybranej strony internetowej (np. [https://www.tryit.org.pl/pl/](https://www.tryit.org.pl/pl/)).

### Nauka składni języka JavaScript

Mając dostęp do interaktywnej konsoli, możemy wykonać zadania z pliku [`czesc_2.js`](https://github.com/m-wojnar/motorola/blob/czesc-2/czesc_2.js). Nawigujemy po kolejnych zdanaiach (commitach):

- [`commit 1d476ab`](https://github.com/m-wojnar/motorola/pull/1/commits/1d476abb6e87ed27c0126eea843b442670138061) Nauka wypisywania na ekran i tworzenia komentarzy
- [`commit 3e8c086`](https://github.com/m-wojnar/motorola/pull/1/commits/3e8c0863064ca86163448193e43e99c3d7aeb93f) Nauka używania zmiennych i operatorów
- [`commit 73465bd`](https://github.com/m-wojnar/motorola/pull/1/commits/73465bdf753097e2ed357de187cef288ddfd541b) Nauka pisania prostych funkcji
- [`commit cf7b028`](https://github.com/m-wojnar/motorola/pull/1/commits/cf7b0288a54e37ceef5047e5a427e5f9e9f68d76) Nauka używania list i obiektów
- [`commit cf34c71`](https://github.com/m-wojnar/motorola/pull/1/commits/cf34c71e9ba61b917004b5cefb943cfa605b95c9) Nauka pisania instrukcji warunkowych (if-else)
- [`commit 2c18ff3`](https://github.com/m-wojnar/motorola/pull/1/commits/2c18ff3d7571c6ce5724846b14ecf1c06ef50ff4) Nauka pisania pętli (for, while)
- [`commit 8841d1f`](https://github.com/m-wojnar/motorola/pull/1/commits/8841d1f8566aa8a2ec0f374d99ef72ac1fa78af9) Nauka tworzenia prostej klasy

#### **Zadanie domowe 2**

Napisz funkcję, której argumentami jest imię i wiek użytkownika. Funkcja powinna zwracać obiekt z imieniem i wiekiem, a także informację o tym czy użytkownik jest dorosły oraz czy jego wiek jest liczbą parzystą. Następnie utwórz listę z 5 imionami i napisz pętlę, która przechodzi po wszystkich elementach listy. W każdej iteracji podaj imię użytkownika i wylosuj wiek. Jeśli wiek użytkownika jest parzysty, wypisz jego dane na ekran.

*Podpowiedź*: poniżej znajduje się funkcja, która pozwala wylosować liczbę całkowitą z zadanego przedziału:
```JavaScript
function getRandomInt(min, max) {
    return Math.floor(Math.random() * (max - min + 1) + min);
}
```

*Rozwiązanie*: przykładowe rozwązanie zadania znajduje się na branchu [`zadanie-domowe-2`](https://github.com/m-wojnar/motorola/pull/2).

### Więcej informacji

Gdzie szukać więcej informacji:
- [The Modern JavaScript Tutorial](https://javascript.info)
- [w3schools](https://www.w3schools.com/js)

#### **Zadanie domowe 3**

W dokumentacji znajdź informacje o typach zmiennych w JS i spróbuj napisać kilka instrukcji warunkowych ze zmiennymi różnych typów

*Rozwiązanie*: przykładowe rozwązanie zadania znajduje się na branchu [`zadanie-domowe-3`](https://github.com/m-wojnar/motorola/pull/5)

## 3. Obiektowy Model Dokumentu

Obiektowy Model Dokumentu (ang. Document Object Model, DOM) to reprezentacja dokumentu HTML w postaci drzewa obiektów. Pozwala na manipulację zawartością strony internetowej za pomocą języka JavaScript. Aby przejść do tej części kursu, należy wykonać komendę:
```bash
git checkout -t origin/czesc-3

# lub, jeżeli branch został wcześniej pobrany na lokalne repozytorium:
git checkout czesc-3
```

### Praca z DOM

W tej części, kursant poznaje DOM poprzez następujące zadania:

- [`commit d63ba6e`](https://github.com/m-wojnar/motorola/pull/3/commits/d63ba6e2ed418f178ecb1fb0394ddb53bd6dbd9a) Szablon strony
- [`commit 359e458`](https://github.com/m-wojnar/motorola/pull/3/commits/359e458158a001f449252e8005d1b619c4b992a4) Nauka wyświetlania alertów i okienek dialogowych
- [`commit a043051`](https://github.com/m-wojnar/motorola/pull/3/commits/a043051bba29066368c53eab7b25b0891c455cf7) Nauka manipulowania elementami
- [`commit fc6ac1d`](https://github.com/m-wojnar/motorola/pull/3/commits/fc6ac1d621ca229ede189877ba31a8bd1df04f28) Nauka reagowania na akcje użytkownika
- [`commit 1cdbde4`](https://github.com/m-wojnar/motorola/pull/3/commits/1cdbde45eb06b0025c755d99efbec1ab9e41331f) Nauka ustawiania opóźnień czasowych (timeouts)
- [`commit 94fa2f6`](https://github.com/m-wojnar/motorola/pull/3/commits/94fa2f60965d3bdd24fd69c5b824fd0bc8dd7424) Nauka ustawiania interwałów

#### **Zadanie domowe 4**

Zmień kolor pudełka na jasnozielony, jeśli liczba kliknięć jest parzysta, a w przeciwnym przypadku zmień kolor na czerwony.

*Rozwiązanie*: przykładowe rozwązanie zadania znajduje się na branchu [`zadanie-domowe-4`](https://github.com/m-wojnar/motorola/pull/4).

## 4. Gra w Łapanie Jabłek

Ostatnia część kursu to zebranie wszystkich dotychczasowych umiejętności w jednym projekcie - grze w łapanie jabłek. Aby przejść do tej części kursu, należy wykonać komendę:
```bash
git checkout -t origin/czesc-4

# lub, jeżeli branch został wcześniej pobrany na lokalne repozytorium:
git checkout czesc-4
```

### PixiJS

PixiJS to biblioteka JavaScript, która ułatwia tworzenie gier i animacji 2D w przeglądarce. Działa jak zestaw narzędzi, które pozwalają rysować, animować i dodawać interakcje do elementów graficznych, takich jak obrazki czy kształty. Wykorzystamy PixiJS do stworzyć gry, w której postać poruszają się po planszy, reagują na kliknięcia klawiaturą, a wszystko wygląda atrakcyjnie i działa płynnie. Wykorzystywane elementy biblioteki PixiJS będziemy tłumaczyć na bieżąco, w trakcie tworzenia gry.

Jeśli chcesz dowiedzieć się więcej o PixiJS, zapraszamy do zapoznania się z literaturą:
- [Dokumentacja PixiJS](https://pixijs.com/8.x/guides)
- [Interaktywny samouczek](https://pixijs.com/8.x/tutorials/getting-started#1)

### Projektowanie gry

W tej części kursu, kursant poznaje podstawy tworzenia gier w PixiJS poprzez projekt gry w łapanie jabłek. Zadania skłądające się na projekt:

- [`commit 1080bb2`](https://github.com/m-wojnar/motorola/pull/6/commits/1080bb2bdc0f82611c66669b01960fb35980a2c0) Szablon strony
- [`commit c19b8ad`](https://github.com/m-wojnar/motorola/pull/6/commits/c19b8ad03da075fa1316efa2a2ccea858de4f3b9) Dodanie skryptów PixiJS
- [`commit 68ed9e7`](https://github.com/m-wojnar/motorola/pull/6/commits/68ed9e7273fc3c9118a6bb1ce72e5e14b6a33fbe) Stworzenie aplikacji PixiJS
- [`commit a9d1160`](https://github.com/m-wojnar/motorola/pull/6/commits/a9d116079392bee5090cf204caff7a1c1f14d239) Dodanie pierwszego zasobu (gracz.png) i stworzenie gracza
- [`commit ea394c6`](https://github.com/m-wojnar/motorola/pull/6/commits/ea394c6ee9d79162c1fd9d31ccfd0e9b3ec033a1) Załadowanie i dodanie tła
- [`commit f06f83a`](https://github.com/m-wojnar/motorola/pull/6/commits/f06f83a6389b9e5db20b9461b11516fd2917dd8b) Sterowanie klawiaturą
- [`commit 8ee0b38`](https://github.com/m-wojnar/motorola/pull/6/commits/8ee0b38a41de602c9eb0b631504913c5a8353b0b) Spadające obiekty
- [`commit 20fdec0`](https://github.com/m-wojnar/motorola/pull/6/commits/20fdec04c9bb3a4d252960d5f15bd4f2c91c6ccf) Aktualizacja pozycji spadających obiektów
- [`commit 746dea2`](https://github.com/m-wojnar/motorola/pull/6/commits/746dea20a4248ff0d9b5947958c8a8cb4b16ce08) Wykrywanie kolizji
- [`commit cb050df`](https://github.com/m-wojnar/motorola/pull/6/commits/cb050df89d5ad6ee6438d17824a71a3d63a8a932) Wyświetlanie wyniku i liczby żyć
- [`commit b4ff922`](https://github.com/m-wojnar/motorola/pull/6/commits/b4ff922bbcd46fc5233d240f893d453f85871a21) Ładowanie i dodawanie dźwięków
- [`commit c367def`](https://github.com/m-wojnar/motorola/pull/6/commits/c367def6e783fffaa73f571250215750e1341b66) Zwiększanie trudności gry z czasem

#### **Zadanie domowe 5**
1. Zmień teksturę gracza w zależności od ruchu (twarz w lewo lub w prawo).  
   *Podpowiedź*: obiekt można odbić lustrzanie przez ustawienie ujemnej skali.
2. Dodaj wiatr - spraw, aby jabłka spadały krzywo (pamiętaj, że jabłka nie mogą wyjść poza ekran!)
3. Dodaj restart (naciśnij spację na początku i po zakończeniu gry)
4. Dodaj tablicę wyników (pokaż 3 najlepsze wyniki na ekranie końca gry)

*Rozwiązanie*: przykładowe rozwązanie zadania znajduje się na branchu [`zadanie-domowe-5`](https://github.com/m-wojnar/motorola/pull/7).

## 5. Podsumowanie

Gratulacje! Ukończyłeś podstawowy kurs języka JavaScript. Teraz powinieneś znać podstawy składni języka, umieć pracować z DOM, a także tworzyć proste gry w PixiJS. Jeśli masz jakieś pytania, uwagi lub sugestie, napisz do nas na adres: TODO

Całość rozwiązań znajdziesz na branchu [`wszysto`](https://github.com/m-wojnar/motorola/tree/wszystko).
