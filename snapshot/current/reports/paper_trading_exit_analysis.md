# Analisi uscite paper trading a leva

Generato: 2026-07-23T17:38:51+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **923**
- Trade con percorso cronologico utilizzabile: **869**
- Trade che hanno raggiunto almeno +€50: **379**
- Di questi, chiusi poi in perdita: **81**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€291,80 | +€1.700,96 |
| 2 | Take profit fisso +€100 | -€1.879,37 | +€113,39 |
| 3 | Strategia attuale | -€1.992,76 | €0,00 |
| 4 | Take profit fisso +€150 | -€1.992,76 | €0,00 |
| 5 | Take profit fisso +€200 | -€1.992,76 | €0,00 |
| 6 | Chiude 50% a +€50 | -€2.141,72 | -€148,96 |
| 7 | Protegge +€20 dopo +€50 | -€2.525,57 | -€532,81 |
| 8 | Protegge +€30 dopo +€50 | -€2.612,68 | -€619,92 |
| 9 | Take profit fisso +€75 | -€2.981,42 | -€988,66 |
| 10 | Pareggio dopo +€50 | -€3.000,20 | -€1.007,44 |
| 11 | Trailing 20% dopo +€50 | -€3.750,11 | -€1.757,35 |
| 12 | TP +€50 / SL -€50 | -€5.322,98 | -€3.330,22 |
| 13 | Take profit fisso +€25 | -€6.430,47 | -€4.437,71 |
| 14 | Take profit fisso +€50 | -€7.039,93 | -€5.047,17 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
