# Specyfikacje – Carpooling (SDD)

Ten katalog to warstwa **specyfikacji** w podejściu Spec-Driven Development.
Opisuje **co** system ma robić i **po co** – bez decyzji technicznych (te trafiają do planu technicznego).

## Struktura

```
specs/
├── README.md                      ← ten plik: zasady i indeks
├── wymagania-niefunkcjonalne.md   ← NF-xx, wspólne dla całego systemu
├── slownik.md                     ← pojęcia domenowe
├── _szablony/                     ← szablony epiku i funkcjonalności
└── E<n>-<nazwa-epiku>/            ← folder = epik (obszar funkcjonalny, 1 osoba)
    ├── README.md                  ← opis epiku: cel, zakres, lista funkcjonalności
    └── F-<nn>-<nazwa>.md          ← funkcjonalność: user stories + kryteria akceptacji
```

## Hierarchia

| Poziom | Plik | Jira |
|---|---|---|
| Epik | `E<n>-.../README.md` | Epic |
| Funkcjonalność | `F-<nn>-....md` | (grupa stories, opcjonalnie label `F-nn`) |
| User story | sekcja `US-<nn>.<i>` w pliku funkcjonalności | Story |
| Zadanie techniczne | plan techniczny (`*.plan.md`) | Sub-task |

## Konwencje

- **ID:** epiki `E1…E6`, funkcjonalności `F-01…` (dziesiątki odpowiadają epikowi: E2 → F-1x), stories `US-<nn>.<i>`, wymagania niefunkcjonalne `NF-xx`.
- **Priorytet (MoSCoW):** Must (MVP) · Should · Could · Won't.
- **Kryteria akceptacji** w formacie **GDY … WTEDY …** / **JEŻELI … TO …** (notacja EARS) – każde kryterium = co najmniej jeden test.
- **Bez technologii** w specyfikacji: nie piszemy o tabelach, endpointach ani frameworkach.
- **Otwarte pytania** oznaczamy `[?]` – specyfikacja z otwartymi pytaniami nie może zostać zatwierdzona.

## Cykl życia specyfikacji

`Szkic` → `Do review` → `Zatwierdzona` → `W realizacji` → `Zrealizowana`

1. Właściciel epiku pisze/uzupełnia specyfikację (**Szkic**).
2. Pull Request ze zmianą specyfikacji → review co najmniej 1 osoby + PO (**Do review**).
3. Po akceptacji (**Zatwierdzona**) stories trafiają do Jiry jako Story pod epikiem.
4. Przed implementacją powstaje plan techniczny i sub-taski (**W realizacji**).
5. Po spełnieniu wszystkich kryteriów akceptacji (**Zrealizowana**).

Zmiana wymagań = najpierw zmiana specyfikacji, potem kodu.

## Epiki

| Epik | Funkcjonalności | Właściciel |
|---|---|---|
| [E1 Konta i profile](E1-konta-i-profile/README.md) | F-01, F-02, F-03, F-04, F-05, F-06 | — |
| [E2 Publikacja przejazdów](E2-publikacja-przejazdow/README.md) | F-10, F-11, F-12, F-13, F-14, F-15, F-16 | — |
| [E3 Wyszukiwanie i mapa](E3-wyszukiwanie-i-mapa/README.md) | F-20, F-21, F-22, F-23, F-24, F-25, F-26 | — |
| [E4 Rezerwacje i komunikacja](E4-rezerwacje-i-komunikacja/README.md) | F-30, F-31, F-32, F-33, F-34, F-35, F-36 | — |
| [E5 Rozliczenia i benefity miejskie](E5-rozliczenia-i-benefity-miejskie/README.md) | F-40, F-41, F-42, F-43, F-44, F-45, F-46, F-47 | — |
| [E6 Oceny i bezpieczeństwo](E6-oceny-i-bezpieczenstwo/README.md) | F-50, F-51, F-52, F-53, F-54 | — |

## MVP

Wszystkie funkcjonalności z priorytetem **Must**: konto i profil → pojazd → publikacja przejazdu z trasą i ceną →
wyszukiwanie, lista, szczegóły → rezerwacja, akceptacja, anulowanie → zakończenie przejazdu → ocena.
