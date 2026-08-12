# Analisi uscite paper trading a leva

Generato: 2026-08-12T18:43:31+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4567**
- Trade con percorso cronologico utilizzabile: **4513**
- Trade che hanno raggiunto almeno +€50: **1698**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€8.114,88 | +€16.403,17 |
| 2 | TP +€50 / SL -€50 | -€17.558,33 | +€6.959,72 |
| 3 | Chiude 50% a +€50 | -€19.505,72 | +€5.012,33 |
| 4 | Protegge +€30 dopo +€50 | -€20.019,27 | +€4.498,78 |
| 5 | Protegge +€20 dopo +€50 | -€22.133,62 | +€2.384,43 |
| 6 | Strategia attuale | -€24.518,05 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.518,05 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.522,37 | -€4,32 |
| 9 | Take profit fisso +€100 | -€24.862,57 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€24.940,26 | -€422,21 |
| 11 | Pareggio dopo +€50 | -€26.021,06 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.169,82 | -€3.651,77 |
| 13 | Take profit fisso +€50 | -€33.768,79 | -€9.250,74 |
| 14 | Take profit fisso +€25 | -€36.407,82 | -€11.889,77 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
