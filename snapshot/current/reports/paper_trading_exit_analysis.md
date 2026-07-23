# Analisi uscite paper trading a leva

Generato: 2026-07-23T19:38:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **958**
- Trade con percorso cronologico utilizzabile: **904**
- Trade che hanno raggiunto almeno +€50: **394**
- Di questi, chiusi poi in perdita: **88**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€944,55 | +€2.018,37 |
| 2 | Take profit fisso +€100 | -€2.849,53 | +€113,39 |
| 3 | Chiude 50% a +€50 | -€2.867,40 | +€95,52 |
| 4 | Strategia attuale | -€2.962,92 | €0,00 |
| 5 | Take profit fisso +€150 | -€2.962,92 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.962,92 | €0,00 |
| 7 | Protegge +€20 dopo +€50 | -€3.305,99 | -€343,07 |
| 8 | Protegge +€30 dopo +€50 | -€3.343,10 | -€380,18 |
| 9 | Take profit fisso +€75 | -€3.874,69 | -€911,78 |
| 10 | Pareggio dopo +€50 | -€3.880,62 | -€917,70 |
| 11 | Trailing 20% dopo +€50 | -€4.563,11 | -€1.600,20 |
| 12 | TP +€50 / SL -€50 | -€5.740,58 | -€2.777,66 |
| 13 | Take profit fisso +€25 | -€7.286,67 | -€4.323,75 |
| 14 | Take profit fisso +€50 | -€7.774,94 | -€4.812,03 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
