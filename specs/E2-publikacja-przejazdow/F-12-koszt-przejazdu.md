# F-12 Koszt na miejsce

| Pole | Wartość |
|---|---|
| Epik | [E2 Publikacja przejazdów](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Kierowca dzieli koszty przejazdu z pasażerami. System sugeruje cenę i ogranicza ją, aby przejazd nie był usługą zarobkową.

## User stories

### US-12.1 Ustalenie ceny
**Jako** kierowca **chcę** zobaczyć sugerowaną cenę za miejsce i ewentualnie ją zmienić, **aby** uczciwie podzielić koszty.

**Kryteria akceptacji**
- [ ] System sugeruje cenę wg F-40 (dystans × stawka za km / (liczba miejsc + 1)).
- [ ] Kierowca może zmienić cenę w zakresie od 0 do sugerowanej ceny + 20%.
- [ ] JEŻELI cena przekracza limit, TO system nie pozwala zapisać przejazdu i pokazuje dopuszczalny zakres.

## Zależności
F-11, F-40

## Poza zakresem
Dynamiczne ceny.

## Otwarte pytania
- [?] Jaka stawka za km? Czy limit +20% jest rozsądny?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-12-koszt-przejazdu.plan.md`._
