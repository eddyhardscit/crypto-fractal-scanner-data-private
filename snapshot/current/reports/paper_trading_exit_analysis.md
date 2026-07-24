# Analisi uscite paper trading a leva

Generato: 2026-07-24T21:09:03+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1217**
- Trade con percorso cronologico utilizzabile: **1163**
- Trade che hanno raggiunto almeno +€50: **546**
- Di questi, chiusi poi in perdita: **131**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€168,53 | +€2.745,21 |
| 2 | Chiude 50% a +€50 | -€1.217,89 | +€1.695,84 |
| 3 | Take profit fisso +€100 | -€2.567,39 | +€346,34 |
| 4 | Protegge +€30 dopo +€50 | -€2.618,01 | +€295,72 |
| 5 | Protegge +€20 dopo +€50 | -€2.884,94 | +€28,79 |
| 6 | Strategia attuale | -€2.913,73 | €0,00 |
| 7 | Take profit fisso +€150 | -€2.913,73 | €0,00 |
| 8 | Take profit fisso +€200 | -€2.913,73 | €0,00 |
| 9 | Trailing 20% dopo +€50 | -€3.554,71 | -€640,98 |
| 10 | Take profit fisso +€75 | -€3.580,16 | -€666,43 |
| 11 | Pareggio dopo +€50 | -€3.703,60 | -€789,87 |
| 12 | TP +€50 / SL -€50 | -€4.464,28 | -€1.550,55 |
| 13 | Take profit fisso +€50 | -€7.225,48 | -€4.311,74 |
| 14 | Take profit fisso +€25 | -€7.263,74 | -€4.350,01 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
