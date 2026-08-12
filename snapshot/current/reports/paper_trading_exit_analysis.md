# Analisi uscite paper trading a leva

Generato: 2026-08-12T17:43:48+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4556**
- Trade con percorso cronologico utilizzabile: **4502**
- Trade che hanno raggiunto almeno +€50: **1687**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€8.773,57 | +€16.403,17 |
| 2 | TP +€50 / SL -€50 | -€18.108,33 | +€7.068,41 |
| 3 | Chiude 50% a +€50 | -€20.110,06 | +€5.066,68 |
| 4 | Protegge +€30 dopo +€50 | -€20.681,09 | +€4.495,65 |
| 5 | Protegge +€20 dopo +€50 | -€22.792,31 | +€2.384,43 |
| 6 | Strategia attuale | -€25.176,74 | €0,00 |
| 7 | Take profit fisso +€200 | -€25.176,74 | €0,00 |
| 8 | Take profit fisso +€150 | -€25.181,06 | -€4,32 |
| 9 | Take profit fisso +€100 | -€25.521,26 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€25.614,66 | -€437,92 |
| 11 | Pareggio dopo +€50 | -€26.679,75 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.895,24 | -€3.718,50 |
| 13 | Take profit fisso +€50 | -€34.318,79 | -€9.142,05 |
| 14 | Take profit fisso +€25 | -€36.682,82 | -€11.506,08 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
