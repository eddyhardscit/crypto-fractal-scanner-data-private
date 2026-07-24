# Analisi uscite paper trading a leva

Generato: 2026-07-24T05:53:54+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1069**
- Trade con percorso cronologico utilizzabile: **1015**
- Trade che hanno raggiunto almeno +€50: **465**
- Di questi, chiusi poi in perdita: **103**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€13,80 | +€2.281,27 |
| 2 | Chiude 50% a +€50 | -€1.563,00 | +€732,07 |
| 3 | Take profit fisso +€100 | -€2.204,83 | +€90,24 |
| 4 | Protegge +€30 dopo +€50 | -€2.284,69 | +€10,38 |
| 5 | Strategia attuale | -€2.295,07 | €0,00 |
| 6 | Take profit fisso +€150 | -€2.295,07 | €0,00 |
| 7 | Take profit fisso +€200 | -€2.295,07 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€2.460,66 | -€165,59 |
| 9 | Take profit fisso +€75 | -€3.110,68 | -€815,61 |
| 10 | Pareggio dopo +€50 | -€3.200,45 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€3.232,49 | -€937,42 |
| 12 | TP +€50 / SL -€50 | -€4.483,43 | -€2.188,36 |
| 13 | Take profit fisso +€50 | -€6.780,69 | -€4.485,62 |
| 14 | Take profit fisso +€25 | -€6.976,83 | -€4.681,76 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
