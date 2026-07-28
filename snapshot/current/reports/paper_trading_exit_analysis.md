# Analisi uscite paper trading a leva

Generato: 2026-07-28T17:42:09+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3187**
- Trade con percorso cronologico utilizzabile: **3133**
- Trade che hanno raggiunto almeno +€50: **1322**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.279,17 | +€11.308,88 |
| 2 | Chiude 50% a +€50 | -€738,23 | +€2.291,47 |
| 3 | Protegge +€30 dopo +€50 | -€1.814,71 | +€1.215,00 |
| 4 | Protegge +€20 dopo +€50 | -€2.578,43 | +€451,28 |
| 5 | Strategia attuale | -€3.029,71 | €0,00 |
| 6 | Take profit fisso +€200 | -€3.029,71 | €0,00 |
| 7 | Take profit fisso +€150 | -€3.034,02 | -€4,32 |
| 8 | TP +€50 / SL -€50 | -€3.080,66 | -€50,95 |
| 9 | Take profit fisso +€100 | -€3.236,74 | -€207,03 |
| 10 | Trailing 20% dopo +€50 | -€3.349,91 | -€320,20 |
| 11 | Pareggio dopo +€50 | -€4.209,73 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€7.539,96 | -€4.510,25 |
| 13 | Take profit fisso +€50 | -€14.251,41 | -€11.221,70 |
| 14 | Take profit fisso +€25 | -€14.721,63 | -€11.691,93 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
