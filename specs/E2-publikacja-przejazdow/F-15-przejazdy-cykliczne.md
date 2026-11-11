# F-15 Przejazdy cykliczne

| Pole | Wartość |
|---|---|
| Epik | [E2 Publikacja przejazdów](README.md) |
| Priorytet | Should |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Kierowca, który regularnie pokonuje tę samą trasę, publikuje ją raz dla wybranych dni tygodnia.

## User stories

### US-15.1 Utworzenie serii
**Jako** kierowca dojeżdżający codziennie do pracy **chcę** opublikować przejazd powtarzany w wybrane dni tygodnia, **aby** nie tworzyć go ręcznie każdego dnia.

**Kryteria akceptacji**
- [ ] Kierowca wybiera dni tygodnia, godzinę i datę końca serii (maks. 3 miesiące).
- [ ] System tworzy pojedyncze przejazdy na najbliższe 14 dni i na bieżąco dogenerowuje kolejne.
- [ ] Każde wystąpienie można rezerwować osobno.

### US-15.2 Anulowanie w serii
**Jako** kierowca **chcę** anulować jedno wystąpienie lub całą serię, **aby** dostosować przejazdy do zmiany planów.

**Kryteria akceptacji**
- [ ] GDY kierowca anuluje wystąpienie lub serię, WTEDY pasażerowie z rezerwacjami dostają powiadomienie (F-34), a rezerwacje są anulowane.

## Zależności
F-10

## Poza zakresem
Rezerwacja całej serii jednym kliknięciem (do rozważenia później).

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-15-przejazdy-cykliczne.plan.md`._
