# F-25 Lokalizacja i wybór punktu na mapie

| Pole | Wartość |
|---|---|
| Epik | [E3 Wyszukiwanie i mapa](README.md) |
| Priorytet | Should |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Szybkie wskazanie punktu startu bez wpisywania adresu.

## User stories

### US-25.1 Moja lokalizacja
**Jako** pasażer **chcę** użyć bieżącej lokalizacji lub wskazać punkt na mapie, **aby** nie wpisywać adresu ręcznie.

**Kryteria akceptacji**
- [ ] GDY użytkownik wybierze „Moja lokalizacja” i udzieli zgody, WTEDY pole „skąd” zostaje uzupełnione.
- [ ] JEŻELI użytkownik odmówi zgody na lokalizację, TO aplikacja działa dalej z ręcznym wpisywaniem adresu.
- [ ] Przytrzymanie palca na mapie ustawia punkt i wyświetla jego adres.

## Zależności
F-20

## Poza zakresem
Śledzenie lokalizacji w tle.

## Otwarte pytania
- brak

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-25-lokalizacja-i-wybor-na-mapie.plan.md`._
