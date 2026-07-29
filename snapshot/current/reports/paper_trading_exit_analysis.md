# Analisi uscite paper trading a leva

Generato: 2026-07-29T10:10:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3381**
- Trade con percorso cronologico utilizzabile: **3327**
- Trade che hanno raggiunto almeno +€50: **1380**
- Di questi, chiusi poi in perdita: **276**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.441,96 | +€11.979,04 |
| 2 | Chiude 50% a +€50 | -€3.808,77 | +€2.728,30 |
| 3 | Protegge +€30 dopo +€50 | -€5.213,08 | +€1.324,00 |
| 4 | Protegge +€20 dopo +€50 | -€5.985,90 | +€551,18 |
| 5 | TP +€50 / SL -€50 | -€6.103,83 | +€433,24 |
| 6 | Strategia attuale | -€6.537,07 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.537,07 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.541,39 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.752,31 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€7.093,46 | -€556,39 |
| 11 | Pareggio dopo +€50 | -€7.666,18 | -€1.129,10 |
| 12 | Take profit fisso +€75 | -€10.749,02 | -€4.211,95 |
| 13 | Take profit fisso +€50 | -€17.943,82 | -€11.406,74 |
| 14 | Take profit fisso +€25 | -€18.183,21 | -€11.646,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
