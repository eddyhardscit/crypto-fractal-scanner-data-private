# Analisi uscite paper trading a leva

Generato: 2026-07-25T03:09:16+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1261**
- Trade con percorso cronologico utilizzabile: **1207**
- Trade che hanno raggiunto almeno +€50: **578**
- Di questi, chiusi poi in perdita: **140**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€1.090,79 | +€2.782,68 |
| 2 | Chiude 50% a +€50 | -€13,97 | +€1.677,92 |
| 3 | Take profit fisso +€100 | -€1.403,90 | +€287,99 |
| 4 | Strategia attuale | -€1.691,89 | €0,00 |
| 5 | Take profit fisso +€150 | -€1.691,89 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.691,89 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€1.796,84 | -€104,96 |
| 8 | Protegge +€20 dopo +€50 | -€2.123,77 | -€431,89 |
| 9 | Take profit fisso +€75 | -€2.739,02 | -€1.047,13 |
| 10 | Pareggio dopo +€50 | -€2.865,43 | -€1.173,54 |
| 11 | Trailing 20% dopo +€50 | -€3.023,97 | -€1.332,08 |
| 12 | TP +€50 / SL -€50 | -€3.945,05 | -€2.253,16 |
| 13 | Take profit fisso +€50 | -€6.743,72 | -€5.051,84 |
| 14 | Take profit fisso +€25 | -€7.097,13 | -€5.405,25 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
