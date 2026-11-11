# F-10 Utworzenie przejazdu

| Pole | Wartość |
|---|---|
| Epik | [E2 Publikacja przejazdów](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Kierowca publikuje planowany przejazd z wolnymi miejscami.

## User stories

### US-10.1 Publikacja przejazdu
**Jako** kierowca **chcę** opublikować przejazd z punktem startu, celem, datą i liczbą miejsc, **aby** zabrać pasażerów jadących w tym samym kierunku.

**Kryteria akceptacji**
- [ ] Wymagane: start i cel (adres z podpowiedziami lub punkt na mapie), data i godzina odjazdu, liczba wolnych miejsc, pojazd.
- [ ] Data odjazdu musi być co najmniej 30 min w przyszłości.
- [ ] Liczba miejsc nie może przekraczać liczby miejsc w wybranym pojeździe.
- [ ] Start i cel muszą leżeć w obszarze działania aplikacji (NF-07).
- [ ] GDY przejazd zostanie opublikowany, WTEDY jest widoczny w wyszukiwaniu (E3) ze statusem „Zaplanowany”.
- [ ] JEŻELI kierowca nie ma pojazdu, TO zostaje przekierowany do dodania pojazdu (F-04).

## Zależności
F-04, F-11, F-12

## Poza zakresem
Przejazdy międzymiastowe.

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-10-utworzenie-przejazdu.plan.md`._
