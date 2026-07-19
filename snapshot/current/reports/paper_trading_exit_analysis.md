# Analisi uscite paper trading a leva

Generato: 2026-07-19T19:08:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **281**
- Trade con percorso cronologico utilizzabile: **227**
- Trade che hanno raggiunto almeno +€50: **121**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.123,27 | +€338,71 |
| 2 | Protegge +€20 dopo +€50 | +€1.990,99 | +€206,43 |
| 3 | Stop loss fisso -€50 | +€1.941,95 | +€157,39 |
| 4 | Take profit fisso +€100 | +€1.874,12 | +€89,56 |
| 5 | Pareggio dopo +€50 | +€1.823,10 | +€38,54 |
| 6 | Strategia attuale | +€1.784,56 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.784,56 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.784,56 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.520,48 | -€264,08 |
| 10 | Trailing 20% dopo +€50 | +€1.352,96 | -€431,60 |
| 11 | Take profit fisso +€75 | +€1.136,24 | -€648,33 |
| 12 | TP +€50 / SL -€50 | +€225,13 | -€1.559,43 |
| 13 | Take profit fisso +€50 | +€51,74 | -€1.732,82 |
| 14 | Take profit fisso +€25 | -€805,77 | -€2.590,33 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
