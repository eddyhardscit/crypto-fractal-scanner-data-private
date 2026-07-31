# Analisi uscite paper trading a leva

Generato: 2026-07-31T08:25:19+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3440**
- Trade con percorso cronologico utilizzabile: **3386**
- Trade che hanno raggiunto almeno +€50: **1394**
- Di questi, chiusi poi in perdita: **279**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.468,81 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.613,98 | +€2.911,69 |
| 3 | Protegge +€30 dopo +€50 | -€5.119,84 | +€1.405,83 |
| 4 | TP +€50 / SL -€50 | -€5.760,92 | +€764,75 |
| 5 | Protegge +€20 dopo +€50 | -€5.936,13 | +€589,54 |
| 6 | Strategia attuale | -€6.525,67 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.525,67 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.529,98 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.740,91 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.835,01 | -€309,35 |
| 11 | Pareggio dopo +€50 | -€7.652,64 | -€1.126,97 |
| 12 | Take profit fisso +€75 | -€10.591,77 | -€4.066,10 |
| 13 | Take profit fisso +€50 | -€17.616,35 | -€11.090,68 |
| 14 | Take profit fisso +€25 | -€17.633,49 | -€11.107,82 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
