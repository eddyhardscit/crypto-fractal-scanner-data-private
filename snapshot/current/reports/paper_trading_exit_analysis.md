# Analisi uscite paper trading a leva

Generato: 2026-07-28T07:39:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2859**
- Trade con percorso cronologico utilizzabile: **2805**
- Trade che hanno raggiunto almeno +€50: **1226**
- Di questi, chiusi poi in perdita: **240**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.927,54 | +€10.919,78 |
| 2 | Protegge +€30 dopo +€50 | +€688,71 | +€1.680,95 |
| 3 | Chiude 50% a +€50 | +€347,80 | +€1.340,04 |
| 4 | Protegge +€20 dopo +€50 | -€336,36 | +€655,88 |
| 5 | Strategia attuale | -€992,24 | €0,00 |
| 6 | Take profit fisso +€200 | -€992,24 | €0,00 |
| 7 | Take profit fisso +€150 | -€996,56 | -€4,32 |
| 8 | Trailing 20% dopo +€50 | -€1.031,43 | -€39,18 |
| 9 | Take profit fisso +€100 | -€1.105,10 | -€112,86 |
| 10 | TP +€50 / SL -€50 | -€1.362,60 | -€370,36 |
| 11 | Pareggio dopo +€50 | -€1.565,15 | -€572,91 |
| 12 | Take profit fisso +€75 | -€5.095,76 | -€4.103,52 |
| 13 | Take profit fisso +€50 | -€12.144,25 | -€11.152,01 |
| 14 | Take profit fisso +€25 | -€13.999,64 | -€13.007,40 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
