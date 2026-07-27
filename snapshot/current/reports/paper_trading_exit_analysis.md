# Analisi uscite paper trading a leva

Generato: 2026-07-27T21:24:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2631**
- Trade con percorso cronologico utilizzabile: **2577**
- Trade che hanno raggiunto almeno +€50: **1139**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.709,82 | +€9.643,85 |
| 2 | Protegge +€30 dopo +€50 | +€942,61 | +€876,64 |
| 3 | Chiude 50% a +€50 | +€650,30 | +€584,33 |
| 4 | Strategia attuale | +€65,97 | €0,00 |
| 5 | Take profit fisso +€200 | +€65,97 | €0,00 |
| 6 | Take profit fisso +€100 | +€63,74 | -€2,23 |
| 7 | Take profit fisso +€150 | +€61,66 | -€4,32 |
| 8 | Protegge +€20 dopo +€50 | +€24,68 | -€41,29 |
| 9 | Trailing 20% dopo +€50 | -€122,44 | -€188,41 |
| 10 | Pareggio dopo +€50 | -€728,20 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€1.735,71 | -€1.801,68 |
| 12 | Take profit fisso +€75 | -€3.640,78 | -€3.706,76 |
| 13 | Take profit fisso +€50 | -€11.241,43 | -€11.307,40 |
| 14 | Take profit fisso +€25 | -€14.516,58 | -€14.582,56 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
