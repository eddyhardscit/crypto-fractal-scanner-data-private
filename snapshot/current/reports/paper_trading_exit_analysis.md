# Analisi uscite paper trading a leva

Generato: 2026-08-14T05:12:33+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4922**
- Trade con percorso cronologico utilizzabile: **4868**
- Trade che hanno raggiunto almeno +€50: **1838**
- Di questi, chiusi poi in perdita: **351**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.981,71 | +€18.671,10 |
| 2 | TP +€50 / SL -€50 | -€16.956,40 | +€6.696,42 |
| 3 | Protegge +€30 dopo +€50 | -€18.865,95 | +€4.786,86 |
| 4 | Chiude 50% a +€50 | -€19.805,62 | +€3.847,19 |
| 5 | Protegge +€20 dopo +€50 | -€21.253,13 | +€2.399,69 |
| 6 | Strategia attuale | -€23.652,81 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.652,81 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.657,13 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€23.834,87 | -€182,06 |
| 10 | Take profit fisso +€100 | -€24.171,74 | -€518,92 |
| 11 | Pareggio dopo +€50 | -€25.152,43 | -€1.499,61 |
| 12 | Take profit fisso +€75 | -€28.667,55 | -€5.014,74 |
| 13 | Take profit fisso +€50 | -€35.434,79 | -€11.781,98 |
| 14 | Take profit fisso +€25 | -€40.864,89 | -€17.212,08 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
