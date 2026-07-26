# Analisi uscite paper trading a leva

Generato: 2026-07-26T06:39:17+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1732**
- Trade con percorso cronologico utilizzabile: **1678**
- Trade che hanno raggiunto almeno +€50: **836**
- Di questi, chiusi poi in perdita: **175**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€11.192,27 | +€4.353,98 |
| 2 | Chiude 50% a +€50 | +€7.370,55 | +€532,26 |
| 3 | Protegge +€30 dopo +€50 | +€7.193,99 | +€355,70 |
| 4 | Protegge +€20 dopo +€50 | +€7.096,83 | +€258,54 |
| 5 | Strategia attuale | +€6.838,29 | €0,00 |
| 6 | Take profit fisso +€200 | +€6.838,29 | €0,00 |
| 7 | Take profit fisso +€150 | +€6.837,55 | -€0,74 |
| 8 | Take profit fisso +€100 | +€6.773,59 | -€64,70 |
| 9 | Pareggio dopo +€50 | +€5.976,92 | -€861,37 |
| 10 | Trailing 20% dopo +€50 | +€5.616,54 | -€1.221,75 |
| 11 | Take profit fisso +€75 | +€3.740,10 | -€3.098,20 |
| 12 | TP +€50 / SL -€50 | +€1.806,99 | -€5.031,30 |
| 13 | Take profit fisso +€50 | -€2.408,86 | -€9.247,15 |
| 14 | Take profit fisso +€25 | -€6.246,46 | -€13.084,76 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
