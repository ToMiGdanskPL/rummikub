# ⏳ Rummikub Timer

Nowoczesny, responsywny i elegancki timer stworzony z myślą o rozgrywkach w **Rummikub** oraz inne gry planszowe (dla 2 do 4 graczy). Aplikacja działa bezpośrednio w przeglądarce, dostosowując się do pozycji graczy przy stole dzięki automatycznemu i płynnemu obrotowi interfejsu.

![Wersja](https://img.shields.io/badge/Wersja-1.0.7-orange.svg)
![Licencja](https://img.shields.io/badge/Licencja-MIT-blue.svg)

---

## 🌟 Kluczowe Funkcje

* **Automatyczna rotacja interfejsu przy stole:**
  * **2 graczy:** obrót o `0°` i `180°`
  * **3 graczy:** obrót o `0°`, `120°` i `240°`
  * **4 graczy:** obrót o `0°`, `90°`, `180°` i `270°`
  * *Obrót odbywa się płynnie, zawsze w kierunku zgodnym z ruchem wskazówek zegara (ciągłe przejście bez cofania tarczy).*

* **Elastyczne tryby czasowe:**
  * **Tryby standardowe:** Predefiniowane czasy tury (30s, 60s, 90s, 120s) oraz tryb **Niestandardowy** z dokładną regulacją co 5 sekund.
  * **Tryb Szachowy (dla 2 graczy):** Bank czasu odliczany w dół dla każdego gracza indywidualnie z możliwością regulacji co 15 sekund.
  * **Całkowity Czas Gry:** Główny zegar meczu (domyślnie 25 minut) z opcją regulacji co 1 minutę, kończący rozgrywkę po upływie czasu.

* **Interfejs & Dźwięk:**
  * **Glassmorphism Design:** Nowoczesny wygląd z obsługą trybu ciemnego i jasnego (Dark / Light mode).
  * **Efekty dźwiękowe:** Subtelne sygnały audio przy zmianie tury i odliczaniu końcówki czasu oraz uroczysta fanfara dźwiękowa i konfetti po zakończeniu meczu (wymaga aktywnego dźwięku).
  * **Precyzja:** Silnik czasowy oparty o znacznik czasu (`Date.now()`), zapobiegający opóźnieniom i rozsynchronizowaniu zegara.
  * **Podsumowanie Statystyk:** Statystyki ruchów i wykorzystanego czasu dla każdego z graczy po zakończeniu gry.

---

## 🚀 Jak uruchomić?

Aplikacja jest w pełni mobilna i nie wymaga instalacji serwera ani żaden dodatkowej konfiguracji.

1. Pobierz plik `index.html`.
2. Otwórz plik w dowolnej przeglądarce internetowej na komputerze, tablecie lub telefonie.

> 💡 **Wskazówka:** Możesz włączyć funkcję **GitHub Pages** w ustawieniach tego repozytorium (*Settings -> Pages*), aby uzyskać darmowy, publiczny adres URL do uruchamiania timera na dowolnym smartfonie przy stole.

---

## 🛠️ Użyte Technologie

* **HTML5 & JavaScript (ES6+)** – logika timera i ciągłej rotacji tarczy
* **Tailwind CSS** – stylizacja oraz szklany efekt glassmorphism
* **Tone.js** – synteza i generowanie efektów dźwiękowych
* **Canvas Confetti** – efekty wizualne po zakończeniu rozgrywki
* **Lucide Icons** – ikony interfejsu

---

## 👨‍💻 Autor

Created with ❤️ by **ToMi** with AI.
