# F-24 Dopasowanie „po drodze”

| Pole | Wartość |
|---|---|
| Epik | [E3 Wyszukiwanie i mapa](README.md) |
| Priorytet | Should |
| Status | Szkic |
| Jira | — |
| Właściciel | — |

## Opis
Pasażer znajduje przejazd, nawet gdy jego punkty nie pokrywają się ze startem i celem kierowcy, ale leżą przy trasie.

## User stories

### US-24.1 Przejazd po drodze
**Jako** pasażer **chcę** znaleźć przejazdy, których trasa przechodzi blisko mojego punktu startu i celu, **aby** skorzystać z podwózki, choć kierowca jedzie dalej lub zaczyna wcześniej.

**Kryteria akceptacji**
- [ ] Przejazd pasuje, gdy „skąd” i „dokąd” pasażera leżą w odległości ≤ 500 m od trasy (wartość konfigurowalna).
- [ ] Punkt wsiadania musi wypadać na trasie przed punktem wysiadania.
- [ ] W wynikach widoczny jest sugerowany punkt wsiadania/wysiadania i odległość do przejścia pieszo.
- [ ] Cena dla pasażera jest proporcjonalna do przejechanego odcinka (F-40).

## Zależności
F-11, F-20, F-40

## Poza zakresem
Zmiana trasy kierowcy w celu zabrania pasażera.

## Otwarte pytania
- [?] Czy kierowca musi akceptować punkt wsiadania inny niż jego przystanki?

## Plan techniczny
_Uzupełniany przed implementacją (etap **Plan** w SDD): model danych, endpointy API, ekrany, decyzje. Może zostać wydzielony do pliku `F-24-dopasowanie-po-drodze.plan.md`._
