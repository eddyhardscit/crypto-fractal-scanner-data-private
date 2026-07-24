# Analisi uscite paper trading a leva

Generato: 2026-07-24T22:09:01+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1218**
- Trade con percorso cronologico utilizzabile: **1164**
- Trade che hanno raggiunto almeno +€50: **547**
- Di questi, chiusi poi in perdita: **131**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€73,81 | +€2.745,21 |
| 2 | Chiude 50% a +€50 | -€1.145,53 | +€1.673,49 |
| 3 | Take profit fisso +€100 | -€2.472,68 | +€346,34 |
| 4 | Protegge +€30 dopo +€50 | -€2.523,30 | +€295,72 |
| 5 | Protegge +€20 dopo +€50 | -€2.790,23 | +€28,79 |
| 6 | Strategia attuale | -€2.819,02 | €0,00 |
| 7 | Take profit fisso +€150 | -€2.819,02 | €0,00 |
| 8 | Take profit fisso +€200 | -€2.819,02 | €0,00 |
| 9 | Take profit fisso +€75 | -€3.505,16 | -€686,14 |
| 10 | Trailing 20% dopo +€50 | -€3.511,57 | -€692,55 |
| 11 | Pareggio dopo +€50 | -€3.608,89 | -€789,87 |
| 12 | TP +€50 / SL -€50 | -€4.414,28 | -€1.595,26 |
| 13 | Take profit fisso +€50 | -€7.175,48 | -€4.356,46 |
| 14 | Take profit fisso +€25 | -€7.238,74 | -€4.419,72 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
