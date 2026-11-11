# F-20 Wyszukiwanie przejazdów

| Pole | Wartość |
|---|---|
| Epik | [E3 Wyszukiwanie i mapa](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Pasażer podaje skąd, dokąd i kiedy chce jechać, a system zwraca pasujące przejazdy.

## User stories

### US-20.1 Wyszukiwanie
**Jako** pasażer **chcę** wyszukać przejazdy podając skąd, dokąd i datę, **aby** znaleźć podwózkę.

**Kryteria akceptacji**
- [ ] Wyniki obejmują wyłącznie przejazdy o statusie „Zaplanowany”, z wolnymi miejscami, w wybranym dniu, od bieżącej godziny.
- [ ] Przejazd pasuje, gdy jego start leży w promieniu 1 km od „skąd”, a cel w promieniu 1 km od „dokąd” (wersja MVP; rozszerzenie w F-24).
- [ ] Przejazdy, których kierowcą jest wyszukujący, nie są pokazywane.
- [ ] JEŻELI brak wyników, TO system wyświetla komunikat i proponuje ustawienie alertu (F-26).
- [ ] Wyniki zwracane w < 2 s (NF-03).

## Zależności
E2

## Poza zakresem
Wyszukiwanie wielodniowe.

## Otwarte pytania
- [?] Czy promień 1 km jest odpowiedni w skali miasta?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-20-wyszukiwanie-przejazdow.plan.md`._
