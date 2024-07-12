## 1. VS Code

a) Instalacja VS Code (https://code.visualstudio.com/download)
b) Rozszerzenie "Live Server" (umożliwia automatyczne przeładowywanie strony)

## 2. Czysty JavaScript

a) Konsola dewelopera JS w przeglądarce:
- uruchomienie konsoli (F12, polecana przeglądarka to Chrome)
- możliwość podglądu komunikatów i błędów debugowania
- możliwość interaktywnego uruchamiania kodu JS
- umożliwienie wklejania kodu do konsoli: `allow pasting`
- **zadanie domowe 1:**
    Przeanalizuj zawartość wybranej strony internetowej (np. [https://www.tryit.org.pl/pl/](https://www.tryit.org.pl/pl/)).

b) Uruchomienie przykładów w konsoli JS (z pliku `czesc_2.js`):
- nauka wypisywania na ekran i tworzenia komentarzy
- nauka używania zmiennych i operatorów
- nauka pisania prostych funkcji
- nauka używania list i obiektów
- nauka pisania instrukcji warunkowych (if-else)
- nauka pisania pętli (for, while)
- nauka tworzenia prostej klasy
- **zadanie domowe 2:**
    Napisz funkcję, której argumentami jest imię i wiek użytkownika. Funkcja powinna zwracać obiekt z imieniem i wiekiem, a także informację o tym czy użytkownik jest dorosły oraz czy jego wiek jest liczbą parzystą. Następnie utwórz listę z 5 imionami i napisz pętlę, która przechodzi po wszystkich elementach listy. W każdej iteracji podaj imię użytkownika i wylosuj wiek. Jeśli wiek użytkownika jest parzysty, wypisz jego dane na ekran. *Podpowiedź*: poniżej znajduje się funkcja, która pozwala wylosować liczbę całkowitą z zadanego przedziału:
    ```
    function getRandomInt(min, max) {
        return Math.floor(Math.random() * (max - min + 1) + min);
    }
    ```

c) Proste przykłady manipulacji dokumentem (z pliku czesc_3.html):
- uruchomienie strony ze pomocą "Live Server"
- nauka wyświetlania alertów i okienek dialogowych
- nauka manipulowania elementami
- nauka reagowania na akcje użytkownika
- nauka ustawiania opóźnień czasowych (timeouts) i interwałów
- **zadanie domowe 3:**
    Zmień kolor pudełka na jasnozielony, jeśli liczba kliknięć jest parzysta, a w przeciwnym przypadku zmień kolor na czerwony

d) Gdzie szukać więcej informacji?
- https://javascript.info
- https://www.w3schools.com/js
- **zadanie domowe 4:**
    W dokumentacji znajdź informacje o typach zmiennych w JS i spróbuj napisać kilka instrukcji warunkowych ze zmiennymi różnych typów

## 3. PixiJS

a) Wprowadzenie
b) Dokumentacja:
- [przewodnik](https://pixijs.com/8.x/guides)
- [interaktywny samouczek](https://pixijs.com/8.x/tutorials/getting-started#1)

## 4. Gra!

- Dodanie skryptów PixiJS
- Stworzenie aplikacji PixiJS
- Dodanie pierwszego zasobu (gracz.png) i stworzenie gracza
- Uwaga o prawach autorskich, jak korzystać z własności intelektualnej zgodnie z licencjami, CC0, ([przykładowe źródło zasobów](https://opengameart.org/), skąd pochodzą zasoby dla tej gry)
- Załadowanie i dodanie tła
- Sterowanie klawiaturą (event listener + app.ticker.add)
- Spadające obiekty
- Aktualizacja pozycji spadających obiektów
- Wykrywanie kolizji
- Wyświetlanie wyniku, liczby żyć i końca gry
- Ładowanie i dodawanie dźwięków
- Zwiększanie trudności gry z czasem
- **Zadanie domowe 5:**
    1. Zmień teksturę gracza w zależności od ruchu (twarz w lewo lub w prawo). *Podpowiedź*: obiekt można odbić lustrzanie przez ustawienie ujemnej skali.
    2. Dodaj wiatr - spraw, aby jabłka spadały krzywo (pamiętaj, że jabłka nie mogą wyjść poza ekran!)
    3. Dodaj restart (naciśnij spację na początku i po zakończeniu gry)
    4. Dodaj tablicę wyników (pokaż 3 najlepsze wyniki na ekranie końca gry)