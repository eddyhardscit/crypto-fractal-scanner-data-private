# Analisi uscite paper trading a leva

Generato: 2026-07-24T15:54:00+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1153**
- Trade con percorso cronologico utilizzabile: **1099**
- Trade che hanno raggiunto almeno +€50: **513**
- Di questi, chiusi poi in perdita: **124**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€871,72 | +€2.391,38 |
| 2 | Chiude 50% a +€50 | -€1.657,09 | +€1.606,02 |
| 3 | Take profit fisso +€100 | -€2.905,98 | +€357,12 |
| 4 | Protegge +€30 dopo +€50 | -€3.251,76 | +€11,34 |
| 5 | Strategia attuale | -€3.263,10 | €0,00 |
| 6 | Take profit fisso +€150 | -€3.263,10 | €0,00 |
| 7 | Take profit fisso +€200 | -€3.263,10 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€3.428,69 | -€165,59 |
| 9 | Take profit fisso +€75 | -€3.868,65 | -€605,55 |
| 10 | Pareggio dopo +€50 | -€4.168,49 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€4.278,64 | -€1.015,54 |
| 12 | TP +€50 / SL -€50 | -€5.236,89 | -€1.973,78 |
| 13 | Take profit fisso +€25 | -€7.199,60 | -€3.936,50 |
| 14 | Take profit fisso +€50 | -€7.644,26 | -€4.381,16 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
