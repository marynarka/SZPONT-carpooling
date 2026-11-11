# F-42 Automatyczne rozliczenie

| Pole | Wartość |
|---|---|
| Epik | [E5 Rozliczenia i benefity miejskie](README.md) |
| Priorytet | Should |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Środki przechodzą od pasażera do kierowcy po zakończonym przejeździe.

## User stories

### US-42.1 Rozliczenie
**Jako** pasażer i kierowca **chcę** żeby przejazd rozliczył się automatycznie, **aby** nie załatwiać płatności gotówką.

**Kryteria akceptacji**
- [ ] GDY rezerwacja zostanie potwierdzona, WTEDY kwota jest blokowana w portfelu pasażera.
- [ ] JEŻELI saldo jest niewystarczające, TO rezerwacja nie jest możliwa (komunikat z opcją doładowania).
- [ ] GDY przejazd zostanie zakończony, WTEDY zablokowana kwota trafia do kierowcy.
- [ ] GDY rezerwacja zostanie anulowana/odrzucona/wygaśnie, WTEDY blokada jest zwalniana.

## Zależności
F-41, F-16, F-30

## Poza zakresem
Spory i reklamacje.

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-42-rozliczenie-przejazdu.plan.md`._
