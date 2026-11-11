# F-50 Ocena po przejeździe

| Pole | Wartość |
|---|---|
| Epik | [E6 Oceny i bezpieczeństwo](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Obie strony oceniają się wzajemnie po zakończonym przejeździe.

## User stories

### US-50.1 Ocena kierowcy
**Jako** pasażer **chcę** ocenić kierowcę w skali 1–5 i dodać komentarz, **aby** pomóc innym wybrać zaufanego kierowcę.

**Kryteria akceptacji**
- [ ] Ocena jest możliwa tylko dla rezerwacji o statusie „Zrealizowana”, przez 14 dni od zakończenia przejazdu.
- [ ] Jedna ocena na osobę na przejazd; komentarz opcjonalny, maks. 500 znaków.
- [ ] Ocenę można edytować przez 24 h od wystawienia.

### US-50.2 Ocena pasażera
**Jako** kierowca **chcę** ocenić każdego pasażera, **aby** inni kierowcy wiedzieli, kogo zabierają.

**Kryteria akceptacji**
- [ ] Te same zasady jak przy ocenie kierowcy, osobno dla każdego pasażera.

## Zależności
F-16

## Poza zakresem
—

## Otwarte pytania
- [?] Czy oceny mają być widoczne dopiero, gdy obie strony ocenią (jak w BlaBlaCar)?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-50-ocena-po-przejezdzie.plan.md`._
