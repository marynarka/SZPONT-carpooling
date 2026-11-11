# F-03 Profil użytkownika

| Pole | Wartość |
|---|---|
| Epik | [E1 Konta i profile](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Profil prezentuje użytkownika innym osobom i buduje zaufanie przed wspólnym przejazdem.

## User stories

### US-03.1 Edycja profilu
**Jako** użytkownik **chcę** uzupełnić imię, zdjęcie, krótki opis i numer telefonu, **aby** inni wiedzieli, z kim jadą.

**Kryteria akceptacji**
- [ ] GDY użytkownik zapisze zmiany, WTEDY profil jest zaktualizowany i widoczny dla innych.
- [ ] Zdjęcie: JPG/PNG, maks. 5 MB.
- [ ] Opis: maks. 300 znaków.

### US-03.2 Podgląd cudzego profilu
**Jako** użytkownik **chcę** zobaczyć profil kierowcy lub pasażera, **aby** ocenić, czy chcę z nim jechać.

**Kryteria akceptacji**
- [ ] Widoczne są: imię, zdjęcie, opis, średnia ocena, liczba odbytych przejazdów, opinie, pojazd (dla kierowcy), oznaczenie „zweryfikowany”.
- [ ] Numer telefonu i e-mail NIE są widoczne, dopóki nie istnieje potwierdzona rezerwacja między użytkownikami (NF-06).

### US-03.3 Usunięcie konta
**Jako** użytkownik **chcę** usunąć swoje konto, **aby** skorzystać z prawa do bycia zapomnianym (RODO).

**Kryteria akceptacji**
- [ ] GDY użytkownik potwierdzi usunięcie, WTEDY dane osobowe są anonimizowane, a aktywne przejazdy i rezerwacje anulowane z powiadomieniem drugiej strony.
- [ ] JEŻELI użytkownik ma przejazd w trakcie, TO usunięcie jest zablokowane do jego zakończenia.

## Zależności
F-01

## Poza zakresem
Weryfikacja tożsamości dokumentem.

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-03-profil-uzytkownika.plan.md`._
