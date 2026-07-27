# Analisi uscite paper trading a leva

Generato: 2026-07-27T18:24:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2593**
- Trade con percorso cronologico utilizzabile: **2539**
- Trade che hanno raggiunto almeno +€50: **1120**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.977,49 | +€9.619,27 |
| 2 | Protegge +€30 dopo +€50 | +€551,79 | +€1.193,56 |
| 3 | Chiude 50% a +€50 | +€35,36 | +€677,14 |
| 4 | Protegge +€20 dopo +€50 | -€306,14 | +€335,64 |
| 5 | Strategia attuale | -€641,78 | €0,00 |
| 6 | Take profit fisso +€200 | -€641,78 | €0,00 |
| 7 | Take profit fisso +€150 | -€646,09 | -€4,32 |
| 8 | Trailing 20% dopo +€50 | -€654,45 | -€12,67 |
| 9 | Take profit fisso +€100 | -€725,97 | -€84,19 |
| 10 | Pareggio dopo +€50 | -€1.435,95 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€2.282,41 | -€1.640,63 |
| 12 | Take profit fisso +€75 | -€4.598,40 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€11.763,55 | -€11.121,77 |
| 14 | Take profit fisso +€25 | -€14.802,30 | -€14.160,52 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
