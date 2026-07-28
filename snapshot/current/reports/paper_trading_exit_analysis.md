# Analisi uscite paper trading a leva

Generato: 2026-07-28T01:24:55+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2762**
- Trade con percorso cronologico utilizzabile: **2708**
- Trade che hanno raggiunto almeno +€50: **1185**
- Di questi, chiusi poi in perdita: **240**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.075,82 | +€10.336,88 |
| 2 | Chiude 50% a +€50 | -€623,46 | +€1.637,60 |
| 3 | Protegge +€30 dopo +€50 | -€653,15 | +€1.607,91 |
| 4 | Protegge +€20 dopo +€50 | -€1.741,08 | +€519,98 |
| 5 | Strategia attuale | -€2.261,06 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.261,06 | €0,00 |
| 7 | Take profit fisso +€150 | -€2.265,38 | -€4,32 |
| 8 | Take profit fisso +€100 | -€2.295,92 | -€34,86 |
| 9 | Trailing 20% dopo +€50 | -€2.328,13 | -€67,07 |
| 10 | TP +€50 / SL -€50 | -€2.619,20 | -€358,14 |
| 11 | Pareggio dopo +€50 | -€2.833,97 | -€572,91 |
| 12 | Take profit fisso +€75 | -€6.138,58 | -€3.877,51 |
| 13 | Take profit fisso +€50 | -€12.817,95 | -€10.556,89 |
| 14 | Take profit fisso +€25 | -€13.833,91 | -€11.572,85 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
