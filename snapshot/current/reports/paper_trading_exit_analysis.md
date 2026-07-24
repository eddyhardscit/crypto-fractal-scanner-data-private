# Analisi uscite paper trading a leva

Generato: 2026-07-24T19:09:01+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1185**
- Trade con percorso cronologico utilizzabile: **1131**
- Trade che hanno raggiunto almeno +€50: **537**
- Di questi, chiusi poi in perdita: **124**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€642,25 | +€2.391,38 |
| 2 | Chiude 50% a +€50 | -€294,91 | +€1.454,22 |
| 3 | Take profit fisso +€100 | -€1.402,79 | +€346,34 |
| 4 | Strategia attuale | -€1.749,13 | €0,00 |
| 5 | Take profit fisso +€150 | -€1.749,13 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.749,13 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€1.778,92 | -€29,80 |
| 8 | Protegge +€20 dopo +€50 | -€1.975,85 | -€226,73 |
| 9 | Take profit fisso +€75 | -€2.434,93 | -€685,80 |
| 10 | Pareggio dopo +€50 | -€2.654,51 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€2.852,44 | -€1.103,31 |
| 12 | TP +€50 / SL -€50 | -€4.113,39 | -€2.364,26 |
| 13 | Take profit fisso +€50 | -€6.520,76 | -€4.771,63 |
| 14 | Take profit fisso +€25 | -€6.584,91 | -€4.835,78 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
