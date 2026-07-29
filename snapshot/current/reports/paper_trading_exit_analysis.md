# Analisi uscite paper trading a leva

Generato: 2026-07-28T23:55:07+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3278**
- Trade con percorso cronologico utilizzabile: **3224**
- Trade che hanno raggiunto almeno +€50: **1335**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.655,67 | +€11.788,42 |
| 2 | Chiude 50% a +€50 | -€3.868,47 | +€2.264,29 |
| 3 | Protegge +€30 dopo +€50 | -€4.859,94 | +€1.272,81 |
| 4 | Protegge +€20 dopo +€50 | -€5.663,67 | +€469,09 |
| 5 | TP +€50 / SL -€50 | -€5.758,54 | +€374,22 |
| 6 | Strategia attuale | -€6.132,76 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.132,76 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.137,07 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€6.243,99 | -€111,23 |
| 10 | Take profit fisso +€100 | -€6.339,79 | -€207,03 |
| 11 | Pareggio dopo +€50 | -€7.312,78 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€10.373,49 | -€4.240,73 |
| 13 | Take profit fisso +€50 | -€17.408,83 | -€11.276,07 |
| 14 | Take profit fisso +€25 | -€18.121,92 | -€11.989,17 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
