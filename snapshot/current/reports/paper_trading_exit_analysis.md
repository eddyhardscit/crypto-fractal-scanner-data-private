# Analisi uscite paper trading a leva

Generato: 2026-07-24T06:53:54+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1087**
- Trade con percorso cronologico utilizzabile: **1033**
- Trade che hanno raggiunto almeno +€50: **476**
- Di questi, chiusi poi in perdita: **114**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€474,07 | +€2.316,90 |
| 2 | Chiude 50% a +€50 | -€1.714,27 | +€1.076,70 |
| 3 | Take profit fisso +€100 | -€2.700,72 | +€90,24 |
| 4 | Protegge +€30 dopo +€50 | -€2.780,59 | +€10,38 |
| 5 | Strategia attuale | -€2.790,97 | €0,00 |
| 6 | Take profit fisso +€150 | -€2.790,97 | €0,00 |
| 7 | Take profit fisso +€200 | -€2.790,97 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€2.956,56 | -€165,59 |
| 9 | Take profit fisso +€75 | -€3.606,58 | -€815,61 |
| 10 | Pareggio dopo +€50 | -€3.696,35 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€3.728,39 | -€937,42 |
| 12 | TP +€50 / SL -€50 | -€4.943,70 | -€2.152,73 |
| 13 | Take profit fisso +€25 | -€7.058,46 | -€4.267,50 |
| 14 | Take profit fisso +€50 | -€7.276,59 | -€4.485,62 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
