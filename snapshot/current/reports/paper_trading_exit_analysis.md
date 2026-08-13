# Analisi uscite paper trading a leva

Generato: 2026-08-13T00:45:39+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4669**
- Trade con percorso cronologico utilizzabile: **4615**
- Trade che hanno raggiunto almeno +€50: **1779**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.263,45 | +€16.479,93 |
| 2 | Protegge +€30 dopo +€50 | -€14.187,72 | +€4.555,66 |
| 3 | TP +€50 / SL -€50 | -€14.327,14 | +€4.416,24 |
| 4 | Chiude 50% a +€50 | -€15.025,62 | +€3.717,76 |
| 5 | Protegge +€20 dopo +€50 | -€16.358,95 | +€2.384,43 |
| 6 | Strategia attuale | -€18.743,38 | €0,00 |
| 7 | Take profit fisso +€200 | -€18.743,38 | €0,00 |
| 8 | Take profit fisso +€150 | -€18.747,70 | -€4,32 |
| 9 | Take profit fisso +€100 | -€19.277,93 | -€534,55 |
| 10 | Trailing 20% dopo +€50 | -€19.500,22 | -€756,83 |
| 11 | Pareggio dopo +€50 | -€20.246,39 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€23.636,87 | -€4.893,49 |
| 13 | Take profit fisso +€50 | -€30.614,36 | -€11.870,98 |
| 14 | Take profit fisso +€25 | -€35.247,30 | -€16.503,92 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
