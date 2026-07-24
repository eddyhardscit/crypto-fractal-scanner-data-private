# Analisi uscite paper trading a leva

Generato: 2026-07-24T11:03:19+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1097**
- Trade con percorso cronologico utilizzabile: **1043**
- Trade che hanno raggiunto almeno +€50: **476**
- Di questi, chiusi poi in perdita: **114**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€972,52 | +€2.319,87 |
| 2 | Chiude 50% a +€50 | -€2.215,69 | +€1.076,70 |
| 3 | Take profit fisso +€100 | -€3.202,14 | +€90,24 |
| 4 | Protegge +€30 dopo +€50 | -€3.282,01 | +€10,38 |
| 5 | Strategia attuale | -€3.292,39 | €0,00 |
| 6 | Take profit fisso +€150 | -€3.292,39 | €0,00 |
| 7 | Take profit fisso +€200 | -€3.292,39 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€3.457,98 | -€165,59 |
| 9 | Take profit fisso +€75 | -€4.107,99 | -€815,61 |
| 10 | Pareggio dopo +€50 | -€4.197,77 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€4.229,81 | -€937,42 |
| 12 | TP +€50 / SL -€50 | -€5.442,15 | -€2.149,76 |
| 13 | Take profit fisso +€25 | -€7.559,88 | -€4.267,50 |
| 14 | Take profit fisso +€50 | -€7.778,01 | -€4.485,62 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
