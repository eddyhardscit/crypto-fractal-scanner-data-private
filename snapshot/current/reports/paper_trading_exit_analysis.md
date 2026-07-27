# Analisi uscite paper trading a leva

Generato: 2026-07-27T16:24:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2580**
- Trade con percorso cronologico utilizzabile: **2526**
- Trade che hanno raggiunto almeno +€50: **1111**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.468,78 | +€9.619,27 |
| 2 | Protegge +€30 dopo +€50 | +€292,09 | +€1.442,58 |
| 3 | Chiude 50% a +€50 | -€438,84 | +€711,65 |
| 4 | Protegge +€20 dopo +€50 | -€475,84 | +€674,65 |
| 5 | Trailing 20% dopo +€50 | -€991,84 | +€158,65 |
| 6 | Strategia attuale | -€1.150,49 | €0,00 |
| 7 | Take profit fisso +€200 | -€1.150,49 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.154,81 | -€4,32 |
| 9 | Take profit fisso +€100 | -€1.234,68 | -€84,19 |
| 10 | Pareggio dopo +€50 | -€1.944,67 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€2.722,11 | -€1.571,62 |
| 12 | Take profit fisso +€75 | -€5.107,11 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€12.203,25 | -€11.052,76 |
| 14 | Take profit fisso +€25 | -€15.127,30 | -€13.976,81 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
