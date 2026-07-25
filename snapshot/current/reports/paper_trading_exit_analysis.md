# Analisi uscite paper trading a leva

Generato: 2026-07-25T00:09:11+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1240**
- Trade con percorso cronologico utilizzabile: **1186**
- Trade che hanno raggiunto almeno +€50: **566**
- Di questi, chiusi poi in perdita: **132**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€1.387,17 | +€2.751,27 |
| 2 | Chiude 50% a +€50 | +€41,25 | +€1.405,34 |
| 3 | Take profit fisso +€100 | -€1.076,10 | +€287,99 |
| 4 | Strategia attuale | -€1.364,09 | €0,00 |
| 5 | Take profit fisso +€150 | -€1.364,09 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.364,09 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€1.469,05 | -€104,96 |
| 8 | Protegge +€20 dopo +€50 | -€1.795,98 | -€431,89 |
| 9 | Take profit fisso +€75 | -€2.411,22 | -€1.047,13 |
| 10 | Pareggio dopo +€50 | -€2.537,63 | -€1.173,54 |
| 11 | Trailing 20% dopo +€50 | -€2.696,17 | -€1.332,08 |
| 12 | TP +€50 / SL -€50 | -€3.648,67 | -€2.284,58 |
| 13 | Take profit fisso +€50 | -€6.415,93 | -€5.051,84 |
| 14 | Take profit fisso +€25 | -€6.808,61 | -€5.444,52 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
