# F-01 Rejestracja i logowanie

| Pole | Wartość |
|---|---|
| Epik | [E1 Konta i profile](README.md) |
| Priorytet | Must (MVP) |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Użytkownik zakłada konto za pomocą e-maila i hasła, loguje się, wylogowuje i resetuje hasło.

## User stories

### US-01.1 Rejestracja konta
**Jako** nowy użytkownik **chcę** założyć konto podając e-mail i hasło, **aby** korzystać z aplikacji jako pasażer lub kierowca.

**Kryteria akceptacji**
- [ ] GDY użytkownik poda imię, poprawny e-mail i hasło (min. 8 znaków, w tym cyfra) oraz zaakceptuje regulamin i klauzulę RODO, WTEDY konto zostaje utworzone, a użytkownik jest zalogowany.
- [ ] JEŻELI e-mail jest już zarejestrowany, TO system wyświetla komunikat i nie tworzy konta.
- [ ] JEŻELI regulamin nie został zaakceptowany, TO przycisk „Załóż konto” jest nieaktywny.

### US-01.2 Logowanie
**Jako** zarejestrowany użytkownik **chcę** zalogować się e-mailem i hasłem, **aby** mieć dostęp do swoich przejazdów i rezerwacji.

**Kryteria akceptacji**
- [ ] GDY dane są poprawne, WTEDY użytkownik zostaje zalogowany, a sesja jest zapamiętana na urządzeniu.
- [ ] JEŻELI dane są niepoprawne, TO system wyświetla ogólny komunikat „Nieprawidłowy e-mail lub hasło” (bez wskazania, które pole jest błędne).
- [ ] JEŻELI konto jest zablokowane, TO logowanie jest odrzucone z odpowiednim komunikatem.

### US-01.3 Wylogowanie
**Jako** zalogowany użytkownik **chcę** się wylogować, **aby** nikt inny nie korzystał z mojego konta na tym urządzeniu.

**Kryteria akceptacji**
- [ ] GDY użytkownik wybierze „Wyloguj”, WTEDY sesja jest usuwana z urządzenia i wyświetla się ekran logowania.

### US-01.4 Reset hasła
**Jako** użytkownik, który zapomniał hasła **chcę** ustawić nowe hasło, **aby** odzyskać dostęp do konta.

**Kryteria akceptacji**
- [ ] GDY użytkownik poda e-mail, WTEDY otrzymuje link do ustawienia nowego hasła ważny 1 godzinę.
- [ ] Komunikat po wysłaniu formularza jest taki sam niezależnie od tego, czy e-mail istnieje w systemie.

## Zależności
—

## Poza zakresem
Logowanie przez Google (F-02), weryfikacja telefonu (F-05).

## Otwarte pytania
- [?] Czy wymagamy potwierdzenia e-maila przed pierwszym logowaniem, czy dopiero przed publikacją przejazdu?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-01-rejestracja-i-logowanie.plan.md`._
