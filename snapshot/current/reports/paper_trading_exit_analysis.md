# Analisi uscite paper trading a leva

Generato: 2026-07-27T17:24:42+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2582**
- Trade con percorso cronologico utilizzabile: **2528**
- Trade che hanno raggiunto almeno +€50: **1113**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.488,61 | +€9.619,27 |
| 2 | Protegge +€30 dopo +€50 | +€352,09 | +€1.482,75 |
| 3 | Chiude 50% a +€50 | -€378,93 | +€751,73 |
| 4 | Protegge +€20 dopo +€50 | -€435,84 | +€694,82 |
| 5 | Trailing 20% dopo +€50 | -€914,23 | +€216,43 |
| 6 | Strategia attuale | -€1.130,66 | €0,00 |
| 7 | Take profit fisso +€200 | -€1.130,66 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.134,98 | -€4,32 |
| 9 | Take profit fisso +€100 | -€1.214,86 | -€84,19 |
| 10 | Pareggio dopo +€50 | -€1.924,84 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€2.622,11 | -€1.491,44 |
| 12 | Take profit fisso +€75 | -€5.087,28 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€12.103,25 | -€10.972,58 |
| 14 | Take profit fisso +€25 | -€15.077,30 | -€13.946,63 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
