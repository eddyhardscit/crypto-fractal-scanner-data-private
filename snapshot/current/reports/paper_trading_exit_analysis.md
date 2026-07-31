# Analisi uscite paper trading a leva

Generato: 2026-07-31T07:25:28+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3436**
- Trade con percorso cronologico utilizzabile: **3382**
- Trade che hanno raggiunto almeno +€50: **1394**
- Di questi, chiusi poi in perdita: **279**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.472,06 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.610,73 | +€2.911,69 |
| 3 | Protegge +€30 dopo +€50 | -€5.116,59 | +€1.405,83 |
| 4 | TP +€50 / SL -€50 | -€5.757,67 | +€764,75 |
| 5 | Protegge +€20 dopo +€50 | -€5.932,88 | +€589,54 |
| 6 | Strategia attuale | -€6.522,42 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.522,42 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.526,74 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.737,66 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.831,77 | -€309,35 |
| 11 | Pareggio dopo +€50 | -€7.649,40 | -€1.126,97 |
| 12 | Take profit fisso +€75 | -€10.588,52 | -€4.066,10 |
| 13 | Take profit fisso +€50 | -€17.613,10 | -€11.090,68 |
| 14 | Take profit fisso +€25 | -€17.630,24 | -€11.107,82 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
