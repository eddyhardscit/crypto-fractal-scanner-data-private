# Analisi uscite paper trading a leva

Generato: 2026-07-28T10:39:58+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2906**
- Trade con percorso cronologico utilizzabile: **2852**
- Trade che hanno raggiunto almeno +€50: **1255**
- Di questi, chiusi poi in perdita: **261**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€10.299,07 | +€10.919,78 |
| 2 | Chiude 50% a +€50 | +€1.225,68 | +€1.846,39 |
| 3 | Protegge +€30 dopo +€50 | +€605,66 | +€1.226,37 |
| 4 | Protegge +€20 dopo +€50 | -€255,54 | +€365,18 |
| 5 | Strategia attuale | -€620,71 | €0,00 |
| 6 | Take profit fisso +€200 | -€620,71 | €0,00 |
| 7 | Take profit fisso +€150 | -€625,03 | -€4,32 |
| 8 | Take profit fisso +€100 | -€735,56 | -€114,85 |
| 9 | Trailing 20% dopo +€50 | -€1.132,15 | -€511,43 |
| 10 | TP +€50 / SL -€50 | -€1.353,56 | -€732,85 |
| 11 | Pareggio dopo +€50 | -€1.564,32 | -€943,61 |
| 12 | Take profit fisso +€75 | -€4.886,73 | -€4.266,02 |
| 13 | Take profit fisso +€50 | -€12.135,21 | -€11.514,50 |
| 14 | Take profit fisso +€25 | -€13.207,30 | -€12.586,58 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
