# Analisi uscite paper trading a leva

Generato: 2026-07-26T16:54:24+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1977**
- Trade con percorso cronologico utilizzabile: **1923**
- Trade che hanno raggiunto almeno +€50: **889**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.803,45 | +€8.867,34 |
| 2 | Chiude 50% a +€50 | -€75,57 | +€988,32 |
| 3 | Protegge +€30 dopo +€50 | -€470,50 | +€593,39 |
| 4 | Protegge +€20 dopo +€50 | -€757,61 | +€306,28 |
| 5 | TP +€50 / SL -€50 | -€1.030,76 | +€33,13 |
| 6 | Strategia attuale | -€1.063,89 | €0,00 |
| 7 | Take profit fisso +€200 | -€1.063,89 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.064,63 | -€0,74 |
| 9 | Take profit fisso +€100 | -€1.128,59 | -€64,70 |
| 10 | Trailing 20% dopo +€50 | -€1.632,59 | -€568,70 |
| 11 | Pareggio dopo +€50 | -€1.906,76 | -€842,87 |
| 12 | Take profit fisso +€75 | -€4.164,97 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€9.759,96 | -€8.696,08 |
| 14 | Take profit fisso +€25 | -€14.069,69 | -€13.005,80 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
