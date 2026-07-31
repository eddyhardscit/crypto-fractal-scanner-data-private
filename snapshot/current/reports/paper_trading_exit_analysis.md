# Analisi uscite paper trading a leva

Generato: 2026-07-31T14:40:31+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3470**
- Trade con percorso cronologico utilizzabile: **3416**
- Trade che hanno raggiunto almeno +€50: **1401**
- Di questi, chiusi poi in perdita: **286**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.421,21 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.482,42 | +€3.090,85 |
| 3 | Protegge +€30 dopo +€50 | -€4.949,13 | +€1.624,15 |
| 4 | TP +€50 / SL -€50 | -€5.450,21 | +€1.123,07 |
| 5 | Protegge +€20 dopo +€50 | -€5.835,42 | +€737,86 |
| 6 | Trailing 20% dopo +€50 | -€6.518,78 | +€54,50 |
| 7 | Strategia attuale | -€6.573,28 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.573,28 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.577,59 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.788,51 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.691,93 | -€1.118,65 |
| 12 | Take profit fisso +€75 | -€10.106,05 | -€3.532,78 |
| 13 | Take profit fisso +€50 | -€17.305,64 | -€10.732,36 |
| 14 | Take profit fisso +€25 | -€17.497,78 | -€10.924,50 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
