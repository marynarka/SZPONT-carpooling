# E4 Rezerwacje i komunikacja

| Pole | Wartość |
|---|---|
| Jira (Epic) | — |
| Właściciel | — |
| Role użytkowników | Pasażer, Kierowca |
| Status | Szkic |

## Cel
Pasażer rezerwuje miejsce, kierowca decyduje, kogo zabiera, a obie strony są na bieżąco informowane o zmianach.

## Zakres
- rezerwacja i jej statusy
- akceptacja / odrzucenie, auto-akceptacja
- anulowanie
- lista rezerwacji pasażera
- powiadomienia push
- czat

## Funkcjonalności

| ID | Funkcjonalność | Priorytet | Status |
|---|---|---|---|
| F-30 | [Rezerwacja miejsca](F-30-rezerwacja-miejsca.md) | Must (MVP) | Szkic |
| F-31 | [Akceptacja rezerwacji](F-31-akceptacja-rezerwacji.md) | Must (MVP) | Szkic |
| F-32 | [Anulowanie rezerwacji](F-32-anulowanie-rezerwacji.md) | Must (MVP) | Szkic |
| F-33 | [Moje rezerwacje (pasażer)](F-33-moje-rezerwacje.md) | Must (MVP) | Szkic |
| F-34 | [Powiadomienia push](F-34-powiadomienia.md) | Should | Szkic |
| F-35 | [Auto-akceptacja](F-35-auto-akceptacja.md) | Could | Szkic |
| F-36 | [Czat kierowca–pasażer](F-36-czat.md) | Could | Szkic |

## Statusy rezerwacji
```
Oczekująca → Potwierdzona → Zrealizowana
           ↘ Odrzucona / Anulowana / Wygasła
```

## Zależności
Wymaga E2 i E3. Wyzwala rozliczenia (E5) i oceny (E6).

## Wymagania niefunkcjonalne
[NF-06](../wymagania-niefunkcjonalne.md)
