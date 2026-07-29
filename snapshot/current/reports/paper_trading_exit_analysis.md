# Analisi uscite paper trading a leva

Generato: 2026-07-29T05:55:11+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3356**
- Trade con percorso cronologico utilizzabile: **3302**
- Trade che hanno raggiunto almeno +€50: **1377**
- Di questi, chiusi poi in perdita: **275**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.839,54 | +€11.956,26 |
| 2 | Chiude 50% a +€50 | -€3.456,15 | +€2.660,57 |
| 3 | Protegge +€30 dopo +€50 | -€4.813,88 | +€1.302,83 |
| 4 | Protegge +€20 dopo +€50 | -€5.576,71 | +€540,01 |
| 5 | TP +€50 / SL -€50 | -€5.747,42 | +€369,30 |
| 6 | Strategia attuale | -€6.116,72 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.116,72 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.121,03 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.331,95 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.705,18 | -€588,46 |
| 11 | Pareggio dopo +€50 | -€7.245,82 | -€1.129,10 |
| 12 | Take profit fisso +€75 | -€10.328,66 | -€4.211,95 |
| 13 | Take profit fisso +€50 | -€17.564,63 | -€11.447,91 |
| 14 | Take profit fisso +€25 | -€18.293,93 | -€12.177,22 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
