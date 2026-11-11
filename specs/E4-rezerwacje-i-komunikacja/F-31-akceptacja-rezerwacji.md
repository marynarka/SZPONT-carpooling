# F-31 Akceptacja rezerwacji

| Pole | Wartość |
|---|---|
| Epik | [E4 Rezerwacje i komunikacja](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Kierowca akceptuje lub odrzuca prośby o rezerwację.

## User stories

### US-31.1 Decyzja kierowcy
**Jako** kierowca **chcę** zaakceptować lub odrzucić rezerwację, **aby** decydować, kogo zabieram.

**Kryteria akceptacji**
- [ ] GDY kierowca zaakceptuje, WTEDY status = „Potwierdzona”, liczba wolnych miejsc maleje, a pasażer dostaje powiadomienie.
- [ ] GDY kierowca odrzuci, WTEDY status = „Odrzucona”, a pasażer dostaje powiadomienie.
- [ ] JEŻELI kierowca nie odpowie do 1 h przed odjazdem, TO rezerwacja zmienia status na „Wygasła”.
- [ ] Zaakceptowanie jest niemożliwe, gdy w międzyczasie zabrakło miejsc.

## Zależności
F-30

## Poza zakresem
—

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-31-akceptacja-rezerwacji.plan.md`._
