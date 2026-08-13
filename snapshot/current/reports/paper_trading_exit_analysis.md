# Analisi uscite paper trading a leva

Generato: 2026-08-13T02:44:13+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4715**
- Trade con percorso cronologico utilizzabile: **4661**
- Trade che hanno raggiunto almeno +€50: **1780**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.150,24 | +€17.749,54 |
| 2 | TP +€50 / SL -€50 | -€16.235,19 | +€5.664,59 |
| 3 | Protegge +€30 dopo +€50 | -€17.344,12 | +€4.555,66 |
| 4 | Chiude 50% a +€50 | -€18.192,66 | +€3.707,13 |
| 5 | Protegge +€20 dopo +€50 | -€19.515,35 | +€2.384,43 |
| 6 | Strategia attuale | -€21.899,78 | €0,00 |
| 7 | Take profit fisso +€200 | -€21.899,78 | €0,00 |
| 8 | Take profit fisso +€150 | -€21.904,10 | -€4,32 |
| 9 | Take profit fisso +€100 | -€22.434,34 | -€534,55 |
| 10 | Trailing 20% dopo +€50 | -€22.656,62 | -€756,83 |
| 11 | Pareggio dopo +€50 | -€23.402,79 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€26.793,27 | -€4.893,49 |
| 13 | Take profit fisso +€50 | -€33.792,02 | -€11.892,24 |
| 14 | Take profit fisso +€25 | -€38.449,97 | -€16.550,18 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
