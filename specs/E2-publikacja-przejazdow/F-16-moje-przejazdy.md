# F-16 Moje przejazdy (kierowca)

| Pole | Wartość |
|---|---|
| Epik | [E2 Publikacja przejazdów](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Kierowca zarządza swoimi przejazdami i prowadzi je przez cykl życia: Zaplanowany → W trakcie → Zakończony / Anulowany.

## User stories

### US-16.1 Lista przejazdów
**Jako** kierowca **chcę** zobaczyć nadchodzące i historyczne przejazdy wraz z rezerwacjami, **aby** mieć nad nimi kontrolę.

**Kryteria akceptacji**
- [ ] Lista podzielona na „Nadchodzące” i „Historia”, z liczbą zajętych/wolnych miejsc i oczekujących rezerwacji.

### US-16.2 Edycja i anulowanie
**Jako** kierowca **chcę** edytować lub anulować przejazd, **aby** reagować na zmianę planów.

**Kryteria akceptacji**
- [ ] JEŻELI przejazd nie ma potwierdzonych rezerwacji, TO można edytować wszystkie dane.
- [ ] JEŻELI przejazd ma potwierdzone rezerwacje, TO można zmienić tylko godzinę (± 30 min) i liczbę miejsc (nie mniej niż zarezerwowane); pasażerowie dostają powiadomienie.
- [ ] GDY kierowca anuluje przejazd, WTEDY wszystkie rezerwacje są anulowane z powiadomieniem.

### US-16.3 Rozpoczęcie i zakończenie
**Jako** kierowca **chcę** oznaczyć rozpoczęcie i zakończenie przejazdu, **aby** uruchomić rozliczenie i oceny.

**Kryteria akceptacji**
- [ ] Rozpoczęcie możliwe od 15 min przed planowaną godziną.
- [ ] GDY kierowca zakończy przejazd, WTEDY status = „Zakończony”, rezerwacje = „Zrealizowana”, uruchamia się rozliczenie (F-42) i możliwość oceny (F-50).
- [ ] JEŻELI kierowca nie zakończy przejazdu w ciągu 12 h od planowanej godziny, TO system zamyka go automatycznie.

## Zależności
F-10, F-30

## Poza zakresem
—

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-16-moje-przejazdy.plan.md`._
