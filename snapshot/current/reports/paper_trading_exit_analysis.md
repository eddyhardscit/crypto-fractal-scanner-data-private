# Analisi uscite paper trading a leva

Generato: 2026-07-25T07:09:23+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1331**
- Trade con percorso cronologico utilizzabile: **1277**
- Trade che hanno raggiunto almeno +€50: **632**
- Di questi, chiusi poi in perdita: **143**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€4.375,68 | +€3.115,85 |
| 2 | Chiude 50% a +€50 | +€2.373,52 | +€1.113,69 |
| 3 | Take profit fisso +€100 | +€1.521,82 | +€261,99 |
| 4 | Strategia attuale | +€1.259,83 | €0,00 |
| 5 | Take profit fisso +€150 | +€1.259,83 | €0,00 |
| 6 | Take profit fisso +€200 | +€1.259,83 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | +€923,91 | -€335,92 |
| 8 | Protegge +€20 dopo +€50 | +€815,61 | -€444,22 |
| 9 | Pareggio dopo +€50 | +€139,95 | -€1.119,88 |
| 10 | Take profit fisso +€75 | +€64,37 | -€1.195,45 |
| 11 | Trailing 20% dopo +€50 | -€211,52 | -€1.471,34 |
| 12 | TP +€50 / SL -€50 | -€1.842,30 | -€3.102,13 |
| 13 | Take profit fisso +€50 | -€4.971,23 | -€6.231,05 |
| 14 | Take profit fisso +€25 | -€6.538,40 | -€7.798,22 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
