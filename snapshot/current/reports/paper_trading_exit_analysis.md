# Analisi uscite paper trading a leva

Generato: 2026-07-28T02:24:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2766**
- Trade con percorso cronologico utilizzabile: **2712**
- Trade che hanno raggiunto almeno +€50: **1187**
- Di questi, chiusi poi in perdita: **240**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.144,64 | +€10.336,88 |
| 2 | Chiude 50% a +€50 | -€537,99 | +€1.654,25 |
| 3 | Protegge +€30 dopo +€50 | -€584,33 | +€1.607,91 |
| 4 | Protegge +€20 dopo +€50 | -€1.672,26 | +€519,98 |
| 5 | Strategia attuale | -€2.192,24 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.192,24 | €0,00 |
| 7 | Take profit fisso +€150 | -€2.196,56 | -€4,32 |
| 8 | Take profit fisso +€100 | -€2.227,10 | -€34,86 |
| 9 | Trailing 20% dopo +€50 | -€2.235,86 | -€43,62 |
| 10 | TP +€50 / SL -€50 | -€2.517,07 | -€324,83 |
| 11 | Pareggio dopo +€50 | -€2.765,15 | -€572,91 |
| 12 | Take profit fisso +€75 | -€6.069,76 | -€3.877,51 |
| 13 | Take profit fisso +€50 | -€12.715,82 | -€10.523,58 |
| 14 | Take profit fisso +€25 | -€13.781,78 | -€11.589,54 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
