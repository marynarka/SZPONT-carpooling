# F-35 Auto-akceptacja

| Pole | Wartość |
|---|---|
| Epik | [E4 Rezerwacje i komunikacja](README.md) |
| Priorytet | Could |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Kierowca może pominąć ręczne akceptowanie rezerwacji.

## User stories

### US-35.1 Automatyczne potwierdzanie
**Jako** kierowca **chcę** włączyć automatyczną akceptację rezerwacji, **aby** nie potwierdzać każdej ręcznie.

**Kryteria akceptacji**
- [ ] GDY auto-akceptacja jest włączona, WTEDY nowa rezerwacja od razu otrzymuje status „Potwierdzona”.
- [ ] Ustawienie domyślne w profilu, nadpisywalne dla przejazdu.

## Zależności
F-31

## Poza zakresem
—

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-35-auto-akceptacja.plan.md`._
