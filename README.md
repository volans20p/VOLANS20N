# Kalkulator zlecenia

Lekka, responsywna aplikacja w języku polskim do szybkiego rozliczania robocizny, dojazdów i dodatkowych kosztów.

## Uruchomienie

Nie wymaga instalacji, serwera, frameworka ani zewnętrznych bibliotek. Otwórz plik `index.html` w aktualnej przeglądarce.

## Funkcje

- wyliczanie czasu od wyjazdu z domu do wyjazdu z pracy;
- odejmowanie niepłatnej przerwy;
- osobne stawki za godzinę i kilometr;
- dodatkowe koszty oraz automatyczne podsumowanie;
- zapisywanie wielu zleceń lokalnie w przeglądarce;
- usuwanie zapisanych pozycji;
- eksport zapisanych danych do CSV (arkusz kalkulacyjny);
- drukowanie podsumowania;
- układ dopasowany do telefonu i komputera.

## Prywatność i ograniczenia

Dane są przechowywane wyłącznie w `localStorage` przeglądarki na urządzeniu użytkownika. Nie są wysyłane do żadnego serwera. Wyczyszczenie danych witryny lub pamięci przeglądarki może usunąć zapisane zlecenia, dlatego warto regularnie eksportować CSV.

Aplikacja nie oblicza podatków, VAT ani składek. Wartości są prostym zestawieniem kwot wpisanych przez użytkownika. Dystans należy podawać jako łączną liczbę kilometrów.

## Technologie

Czysty HTML, CSS i JavaScript — bez zależności zewnętrznych.
