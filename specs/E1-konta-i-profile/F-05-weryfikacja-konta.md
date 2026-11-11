# F-05 Weryfikacja konta

| Pole | Wartość |
|---|---|
| Epik | [E1 Konta i profile](README.md) |
| Priorytet | Should |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Potwierdzenie e-maila (i opcjonalnie telefonu) zwiększa wiarygodność użytkowników.

## User stories

### US-05.1 Potwierdzenie e-maila
**Jako** użytkownik **chcę** potwierdzić swój e-mail, **aby** otrzymać oznaczenie „zweryfikowany”.

**Kryteria akceptacji**
- [ ] GDY użytkownik kliknie link z wiadomości, WTEDY e-mail jest oznaczony jako potwierdzony.
- [ ] Link jest ważny 24 h; można wysłać go ponownie z poziomu profilu.

### US-05.2 Potwierdzenie telefonu
**Jako** użytkownik **chcę** potwierdzić numer telefonu kodem SMS, **aby** zwiększyć zaufanie innych.

**Kryteria akceptacji**
- [ ] GDY użytkownik wpisze poprawny kod, WTEDY numer jest oznaczony jako potwierdzony.
- [ ] Maks. 3 próby wysłania kodu na godzinę.

## Zależności
F-01, F-03

## Poza zakresem
Weryfikacja dokumentem tożsamości.

## Otwarte pytania
- [?] SMS jest płatny – czy realizujemy tylko e-mail?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-05-weryfikacja-konta.plan.md`._
