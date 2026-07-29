# Analisi uscite paper trading a leva

Generato: 2026-07-29T06:55:12+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3366**
- Trade con percorso cronologico utilizzabile: **3312**
- Trade che hanno raggiunto almeno +€50: **1380**
- Di questi, chiusi poi in perdita: **276**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.749,52 | +€11.962,35 |
| 2 | Chiude 50% a +€50 | -€3.484,53 | +€2.728,30 |
| 3 | Protegge +€30 dopo +€50 | -€4.888,83 | +€1.324,00 |
| 4 | Protegge +€20 dopo +€50 | -€5.661,65 | +€551,18 |
| 5 | TP +€50 / SL -€50 | -€5.796,27 | +€416,56 |
| 6 | Strategia attuale | -€6.212,83 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.212,83 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.217,14 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.428,07 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.769,22 | -€556,39 |
| 11 | Pareggio dopo +€50 | -€7.341,93 | -€1.129,10 |
| 12 | Take profit fisso +€75 | -€10.424,78 | -€4.211,95 |
| 13 | Take profit fisso +€50 | -€17.619,57 | -€11.406,74 |
| 14 | Take profit fisso +€25 | -€18.329,57 | -€12.116,74 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
