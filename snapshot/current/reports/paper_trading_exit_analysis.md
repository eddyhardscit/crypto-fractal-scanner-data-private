# Analisi uscite paper trading a leva

Generato: 2026-07-19T20:08:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **283**
- Trade con percorso cronologico utilizzabile: **229**
- Trade che hanno raggiunto almeno +€50: **122**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.193,28 | +€338,71 |
| 2 | Protegge +€20 dopo +€50 | +€2.061,00 | +€206,43 |
| 3 | Stop loss fisso -€50 | +€2.011,96 | +€157,39 |
| 4 | Take profit fisso +€100 | +€1.944,13 | +€89,56 |
| 5 | Pareggio dopo +€50 | +€1.893,11 | +€38,54 |
| 6 | Strategia attuale | +€1.854,57 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.854,57 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.854,57 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.578,42 | -€276,15 |
| 10 | Trailing 20% dopo +€50 | +€1.422,97 | -€431,60 |
| 11 | Take profit fisso +€75 | +€1.206,24 | -€648,33 |
| 12 | TP +€50 / SL -€50 | +€270,99 | -€1.583,57 |
| 13 | Take profit fisso +€50 | +€97,61 | -€1.756,96 |
| 14 | Take profit fisso +€25 | -€755,77 | -€2.610,34 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
