# Analisi uscite paper trading a leva

Generato: 2026-07-28T00:24:46+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2729**
- Trade con percorso cronologico utilizzabile: **2675**
- Trade che hanno raggiunto almeno +€50: **1178**
- Di questi, chiusi poi in perdita: **239**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.662,21 | +€10.326,68 |
| 2 | Chiude 50% a +€50 | -€917,41 | +€1.747,06 |
| 3 | Protegge +€30 dopo +€50 | -€1.056,56 | +€1.607,91 |
| 4 | Protegge +€20 dopo +€50 | -€2.144,49 | +€519,98 |
| 5 | Strategia attuale | -€2.664,47 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.664,47 | €0,00 |
| 7 | Take profit fisso +€100 | -€2.666,70 | -€2,23 |
| 8 | Take profit fisso +€150 | -€2.668,79 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€2.676,38 | -€11,91 |
| 10 | TP +€50 / SL -€50 | -€2.712,04 | -€47,58 |
| 11 | Pareggio dopo +€50 | -€3.237,37 | -€572,91 |
| 12 | Take profit fisso +€75 | -€6.371,22 | -€3.706,76 |
| 13 | Take profit fisso +€50 | -€12.900,60 | -€10.236,13 |
| 14 | Take profit fisso +€25 | -€13.842,08 | -€11.177,62 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
