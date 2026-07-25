# Analisi uscite paper trading a leva

Generato: 2026-07-25T08:24:08+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1340**
- Trade con percorso cronologico utilizzabile: **1286**
- Trade che hanno raggiunto almeno +€50: **638**
- Di questi, chiusi poi in perdita: **144**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€4.756,14 | +€3.115,85 |
| 2 | Chiude 50% a +€50 | +€2.704,57 | +€1.064,29 |
| 3 | Take profit fisso +€100 | +€1.902,28 | +€261,99 |
| 4 | Strategia attuale | +€1.640,29 | €0,00 |
| 5 | Take profit fisso +€150 | +€1.640,29 | €0,00 |
| 6 | Take profit fisso +€200 | +€1.640,29 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | +€1.335,12 | -€305,17 |
| 8 | Protegge +€20 dopo +€50 | +€1.216,81 | -€423,47 |
| 9 | Pareggio dopo +€50 | +€521,16 | -€1.119,13 |
| 10 | Take profit fisso +€75 | +€377,73 | -€1.262,56 |
| 11 | Trailing 20% dopo +€50 | +€201,00 | -€1.439,29 |
| 12 | TP +€50 / SL -€50 | -€1.560,65 | -€3.200,94 |
| 13 | Take profit fisso +€50 | -€4.689,58 | -€6.329,87 |
| 14 | Take profit fisso +€25 | -€6.406,75 | -€8.047,04 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
