# Analisi uscite paper trading a leva

Generato: 2026-07-28T04:39:51+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2789**
- Trade con percorso cronologico utilizzabile: **2735**
- Trade che hanno raggiunto almeno +€50: **1200**
- Di questi, chiusi poi in perdita: **240**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.424,52 | +€10.336,88 |
| 2 | Chiude 50% a +€50 | -€81,13 | +€1.831,24 |
| 3 | Protegge +€30 dopo +€50 | -€98,56 | +€1.813,81 |
| 4 | Protegge +€20 dopo +€50 | -€1.256,48 | +€655,88 |
| 5 | Trailing 20% dopo +€50 | -€1.562,47 | +€349,89 |
| 6 | TP +€50 / SL -€50 | -€1.883,22 | +€29,14 |
| 7 | Strategia attuale | -€1.912,36 | €0,00 |
| 8 | Take profit fisso +€200 | -€1.912,36 | €0,00 |
| 9 | Take profit fisso +€150 | -€1.916,68 | -€4,32 |
| 10 | Take profit fisso +€100 | -€1.947,22 | -€34,86 |
| 11 | Pareggio dopo +€50 | -€2.485,27 | -€572,91 |
| 12 | Take profit fisso +€75 | -€5.664,54 | -€3.752,17 |
| 13 | Take profit fisso +€50 | -€12.081,98 | -€10.169,62 |
| 14 | Take profit fisso +€25 | -€13.472,94 | -€11.560,58 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
