# F-30 Rezerwacja miejsca

| Pole | Wartość |
|---|---|
| Epik | [E4 Rezerwacje i komunikacja](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Pasażer rezerwuje miejsce w wybranym przejeździe.

## User stories

### US-30.1 Rezerwacja
**Jako** pasażer **chcę** zarezerwować miejsce w przejeździe, **aby** mieć pewność, że pojadę.

**Kryteria akceptacji**
- [ ] GDY pasażer kliknie „Zarezerwuj” w przejeździe z wolnymi miejscami, WTEDY powstaje rezerwacja o statusie „Oczekująca”, a kierowca dostaje powiadomienie.
- [ ] Pasażer może zarezerwować 1–2 miejsca w jednej rezerwacji (np. dla siebie i osoby towarzyszącej).
- [ ] JEŻELI brak wolnych miejsc, TO przycisk „Zarezerwuj” jest nieaktywny.
- [ ] Pasażer NIE MOŻE rezerwować miejsca we własnym przejeździe.
- [ ] Pasażer NIE MOŻE mieć dwóch aktywnych rezerwacji w tym samym przejeździe.

## Zależności
F-22

## Poza zakresem
Płatność przy rezerwacji (E5).

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-30-rezerwacja-miejsca.plan.md`._
