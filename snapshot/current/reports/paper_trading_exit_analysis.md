# Analisi uscite paper trading a leva

Generato: 2026-07-27T08:09:38+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2278**
- Trade con percorso cronologico utilizzabile: **2224**
- Trade che hanno raggiunto almeno +€50: **1075**
- Di questi, chiusi poi in perdita: **198**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€16.518,45 | +€9.037,67 |
| 2 | Protegge +€30 dopo +€50 | +€8.851,93 | +€1.371,14 |
| 3 | Protegge +€20 dopo +€50 | +€8.134,91 | +€654,13 |
| 4 | Strategia attuale | +€7.480,78 | €0,00 |
| 5 | Take profit fisso +€200 | +€7.480,78 | €0,00 |
| 6 | Take profit fisso +€150 | +€7.476,47 | -€4,32 |
| 7 | Trailing 20% dopo +€50 | +€7.471,95 | -€8,83 |
| 8 | Chiude 50% a +€50 | +€7.466,88 | -€13,90 |
| 9 | Take profit fisso +€100 | +€7.396,59 | -€84,19 |
| 10 | Pareggio dopo +€50 | +€6.686,60 | -€794,18 |
| 11 | TP +€50 / SL -€50 | +€5.117,29 | -€2.363,49 |
| 12 | Take profit fisso +€75 | +€3.524,16 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€3.782,24 | -€11.263,03 |
| 14 | Take profit fisso +€25 | -€11.395,73 | -€18.876,51 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
