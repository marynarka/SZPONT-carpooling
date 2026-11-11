# F-40 Wyliczenie kosztu przejazdu

| Pole | Wartość |
|---|---|
| Epik | [E5 Rozliczenia i benefity miejskie](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Reguła wyliczania kosztu oparta na dzieleniu kosztów, a nie na zarobku.

## User stories

### US-40.1 Sugerowana cena
**Jako** kierowca **chcę** otrzymać sugerowaną cenę za miejsce, **aby** uczciwie podzielić koszty paliwa.

**Kryteria akceptacji**
- [ ] Cena za miejsce = dystans [km] × stawka za km / (liczba miejsc + 1), zaokrąglona do 0,50 zł.
- [ ] Dla dopasowania „po drodze” (F-24) cena jest proporcjonalna do odcinka przejechanego przez pasażera.
- [ ] Stawka za km jest konfigurowalna przez administratora.

### US-40.2 Informacja o koszcie
**Jako** pasażer **chcę** znać koszt przed rezerwacją, **aby** wiedzieć, ile zapłacę.

**Kryteria akceptacji**
- [ ] Cena jest widoczna na liście wyników i w szczegółach przejazdu.
- [ ] Aplikacja informuje, że przejazd to dzielenie kosztów, a nie usługa przewozowa.

## Zależności
F-11

## Poza zakresem
—

## Otwarte pytania
- [?] Stawka za km – wartość domyślna?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-40-wyliczenie-kosztu.plan.md`._
