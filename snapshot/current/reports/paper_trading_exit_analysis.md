# Analisi uscite paper trading a leva

Generato: 2026-07-30T13:10:32+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3426**
- Trade con percorso cronologico utilizzabile: **3372**
- Trade che hanno raggiunto almeno +€50: **1393**
- Di questi, chiusi poi in perdita: **279**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.438,40 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.646,19 | +€2.909,90 |
| 3 | Protegge +€30 dopo +€50 | -€5.150,26 | +€1.405,83 |
| 4 | TP +€50 / SL -€50 | -€5.794,93 | +€761,16 |
| 5 | Protegge +€20 dopo +€50 | -€5.966,55 | +€589,54 |
| 6 | Strategia attuale | -€6.556,09 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.556,09 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.560,40 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.771,32 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.858,18 | -€302,09 |
| 11 | Pareggio dopo +€50 | -€7.683,06 | -€1.126,97 |
| 12 | Take profit fisso +€75 | -€10.650,78 | -€4.094,69 |
| 13 | Take profit fisso +€50 | -€17.650,36 | -€11.094,27 |
| 14 | Take profit fisso +€25 | -€17.747,34 | -€11.191,26 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
