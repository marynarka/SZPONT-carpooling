# F-04 Pojazdy kierowcy

| Pole | Wartość |
|---|---|
| Epik | [E1 Konta i profile](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Kierowca dodaje pojazd, którym realizuje przejazdy. Pasażer widzi, do jakiego auta wsiada.

## User stories

### US-04.1 Dodanie pojazdu
**Jako** kierowca **chcę** dodać swój samochód, **aby** móc publikować przejazdy.

**Kryteria akceptacji**
- [ ] Wymagane pola: marka, model, kolor, numer rejestracyjny, liczba miejsc dla pasażerów (1–8).
- [ ] GDY pojazd zostanie zapisany, WTEDY można go wybrać przy publikacji przejazdu.
- [ ] Bez dodanego pojazdu publikacja przejazdu nie jest możliwa.

### US-04.2 Edycja i usunięcie pojazdu
**Jako** kierowca **chcę** zmienić lub usunąć pojazd, **aby** dane były aktualne.

**Kryteria akceptacji**
- [ ] JEŻELI pojazd jest przypisany do nadchodzących przejazdów, TO nie można go usunąć (komunikat z listą przejazdów).

## Zależności
F-01

## Poza zakresem
Weryfikacja dowodu rejestracyjnego.

## Otwarte pytania
- [?] Czy numer rejestracyjny pokazujemy pasażerowi przed, czy dopiero po potwierdzeniu rezerwacji?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-04-pojazdy.plan.md`._
