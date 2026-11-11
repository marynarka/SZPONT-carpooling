# Wymagania niefunkcjonalne

Dotyczą całego systemu. Specyfikacje funkcjonalności odwołują się do nich po ID.

| ID | Obszar | Wymaganie |
|---|---|---|
| NF-01 | Platforma | Aplikacja mobilna iOS i Android (priorytet); wersja web jako dodatek – głównie panel administratora/miasta. Brak wersji desktop. |
| NF-02 | Język | Interfejs w języku polskim; architektura umożliwia dodanie kolejnych języków. |
| NF-03 | Wydajność | Wyszukiwanie przejazdów zwraca wyniki w < 2 s dla typowego zapytania. |
| NF-04 | Bezpieczeństwo | Hasła hashowane (np. BCrypt), komunikacja wyłącznie HTTPS, autoryzacja tokenami JWT, walidacja danych po stronie serwera. |
| NF-05 | RODO | Zgoda na przetwarzanie danych, możliwość usunięcia konta, minimalizacja danych, statystyki tylko zagregowane. |
| NF-06 | Prywatność | Dane kontaktowe i dokładna lokalizacja udostępniane drugiej stronie dopiero po potwierdzeniu rezerwacji. |
| NF-07 | Obszar działania | Jedno miasto / aglomeracja (np. Białystok) – obszar konfigurowalny. |
| NF-08 | Dostępność | Czytelne kontrasty i rozmiary czcionek, obsługa trybu ciemnego systemu. |
| NF-09 | Testowalność | Każde kryterium akceptacji ma odpowiadający mu test (automatyczny lub manualny scenariusz). |
