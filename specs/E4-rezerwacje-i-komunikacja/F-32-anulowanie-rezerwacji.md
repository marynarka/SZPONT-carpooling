# F-32 Anulowanie rezerwacji

| Pole | Wartość |
|---|---|
| Epik | [E4 Rezerwacje i komunikacja](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Obie strony mogą zrezygnować z rezerwacji.

## User stories

### US-32.1 Anulowanie przez pasażera
**Jako** pasażer **chcę** anulować rezerwację, **aby** zwolnić miejsce, gdy zmienię plany.

**Kryteria akceptacji**
- [ ] GDY pasażer anuluje rezerwację, WTEDY status = „Anulowana”, miejsce wraca do puli, a kierowca dostaje powiadomienie.
- [ ] Anulowanie później niż 2 h przed odjazdem jest odnotowywane w statystykach profilu.

### US-32.2 Anulowanie przez kierowcę
**Jako** kierowca **chcę** anulować potwierdzoną rezerwację konkretnego pasażera, **aby** reagować na nieprzewidziane sytuacje.

**Kryteria akceptacji**
- [ ] Kierowca musi podać powód; pasażer dostaje powiadomienie z powodem.

## Zależności
F-30, F-31

## Poza zakresem
Kary finansowe za późne anulowanie.

## Otwarte pytania
- [?] Jakie konsekwencje późnego anulowania (poza statystyką)?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-32-anulowanie-rezerwacji.plan.md`._
