# Analisi uscite paper trading a leva

Generato: 2026-08-12T22:49:02+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4631**
- Trade con percorso cronologico utilizzabile: **4577**
- Trade che hanno raggiunto almeno +€50: **1746**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€5.324,37 | +€16.470,20 |
| 2 | TP +€50 / SL -€50 | -€15.883,08 | +€5.911,49 |
| 3 | Protegge +€30 dopo +€50 | -€17.238,91 | +€4.555,66 |
| 4 | Chiude 50% a +€50 | -€17.324,32 | +€4.470,25 |
| 5 | Protegge +€20 dopo +€50 | -€19.410,14 | +€2.384,43 |
| 6 | Strategia attuale | -€21.794,57 | €0,00 |
| 7 | Take profit fisso +€200 | -€21.794,57 | €0,00 |
| 8 | Take profit fisso +€150 | -€21.798,89 | -€4,32 |
| 9 | Take profit fisso +€100 | -€22.157,83 | -€363,26 |
| 10 | Trailing 20% dopo +€50 | -€22.551,40 | -€756,83 |
| 11 | Pareggio dopo +€50 | -€23.297,58 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€25.977,08 | -€4.182,51 |
| 13 | Take profit fisso +€50 | -€32.160,56 | -€10.365,99 |
| 14 | Take profit fisso +€25 | -€35.968,51 | -€14.173,94 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
