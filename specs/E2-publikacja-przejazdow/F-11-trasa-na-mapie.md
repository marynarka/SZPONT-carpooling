# F-11 Trasa na mapie

| Pole | Wartość |
|---|---|
| Epik | [E2 Publikacja przejazdów](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
System wyznacza trasę przejazdu, pokazuje ją na mapie i zapisuje do późniejszego dopasowania pasażerów.

## User stories

### US-11.1 Podgląd trasy
**Jako** kierowca **chcę** zobaczyć wyznaczoną trasę, dystans i czas przejazdu, **aby** upewnić się, że trasa jest poprawna.

**Kryteria akceptacji**
- [ ] GDY wybrano start i cel, WTEDY system wyznacza trasę (zewnętrzny serwis tras) i pokazuje ją na mapie z dystansem i szacowanym czasem.
- [ ] Trasa (linia geograficzna) jest zapisywana razem z przejazdem.
- [ ] JEŻELI serwis tras jest niedostępny, TO użytkownik dostaje komunikat i może spróbować ponownie.

## Zależności
F-10

## Poza zakresem
Ręczne rysowanie trasy.

## Otwarte pytania
- [?] Google Directions czy OpenRouteService/OSRM? (ADR w dokumentacji architektury)

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-11-trasa-na-mapie.plan.md`._
