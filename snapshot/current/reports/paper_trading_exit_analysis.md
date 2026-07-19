# Analisi uscite paper trading a leva

Generato: 2026-07-19T15:53:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **271**
- Trade con percorso cronologico utilizzabile: **217**
- Trade che hanno raggiunto almeno +€50: **117**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.960,97 | +€338,71 |
| 2 | Protegge +€20 dopo +€50 | +€1.828,70 | +€206,43 |
| 3 | Stop loss fisso -€50 | +€1.763,00 | +€140,73 |
| 4 | Take profit fisso +€100 | +€1.722,05 | +€99,78 |
| 5 | Pareggio dopo +€50 | +€1.660,81 | +€38,54 |
| 6 | Strategia attuale | +€1.622,26 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.622,26 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.622,26 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.448,85 | -€173,42 |
| 10 | Trailing 20% dopo +€50 | +€1.190,66 | -€431,60 |
| 11 | Take profit fisso +€75 | +€1.056,48 | -€565,79 |
| 12 | TP +€50 / SL -€50 | +€227,48 | -€1.394,78 |
| 13 | Take profit fisso +€50 | +€70,76 | -€1.551,50 |
| 14 | Take profit fisso +€25 | -€686,76 | -€2.309,02 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
