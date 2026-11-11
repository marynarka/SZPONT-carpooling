# F-02 Logowanie przez Google

| Pole | Wartość |
|---|---|
| Epik | [E1 Konta i profile](README.md) |
| Priorytet | Should |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Szybkie założenie konta i logowanie kontem Google.

## User stories

### US-02.1 Logowanie przez Google
**Jako** użytkownik **chcę** zalogować się kontem Google, **aby** nie zakładać kolejnego hasła.

**Kryteria akceptacji**
- [ ] GDY użytkownik loguje się Google po raz pierwszy, WTEDY system tworzy konto z imieniem, e-mailem i zdjęciem z Google.
- [ ] GDY konto z tym e-mailem już istnieje, WTEDY użytkownik zostaje zalogowany na istniejące konto.
- [ ] Użytkownik musi zaakceptować regulamin przy pierwszym logowaniu.

## Zależności
F-01

## Poza zakresem
Logowanie przez Apple/Facebook.

## Otwarte pytania
- [?] Apple wymaga „Sign in with Apple”, jeśli aplikacja w App Store oferuje logowanie innymi kontami – czy publikujemy w sklepie?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-02-logowanie-google.plan.md`._
