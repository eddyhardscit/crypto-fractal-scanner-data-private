# Analisi uscite paper trading a leva

Generato: 2026-07-28T03:39:48+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2775**
- Trade con percorso cronologico utilizzabile: **2721**
- Trade che hanno raggiunto almeno +€50: **1192**
- Di questi, chiusi poi in perdita: **240**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.388,95 | +€10.336,88 |
| 2 | Chiude 50% a +€50 | -€293,51 | +€1.654,42 |
| 3 | Protegge +€30 dopo +€50 | -€340,03 | +€1.607,91 |
| 4 | Protegge +€20 dopo +€50 | -€1.427,95 | +€519,98 |
| 5 | Trailing 20% dopo +€50 | -€1.901,67 | +€46,27 |
| 6 | Strategia attuale | -€1.947,94 | €0,00 |
| 7 | Take profit fisso +€200 | -€1.947,94 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.952,25 | -€4,32 |
| 9 | Take profit fisso +€100 | -€1.982,79 | -€34,86 |
| 10 | TP +€50 / SL -€50 | -€2.272,42 | -€324,49 |
| 11 | Pareggio dopo +€50 | -€2.520,84 | -€572,91 |
| 12 | Take profit fisso +€75 | -€5.700,11 | -€3.752,17 |
| 13 | Take profit fisso +€50 | -€12.471,18 | -€10.523,24 |
| 14 | Take profit fisso +€25 | -€13.662,14 | -€11.714,20 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
