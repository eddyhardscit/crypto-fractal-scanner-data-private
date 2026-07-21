# Analisi uscite paper trading a leva

Generato: 2026-07-21T12:38:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **469**
- Trade con percorso cronologico utilizzabile: **415**
- Trade che hanno raggiunto almeno +€50: **198**
- Di questi, chiusi poi in perdita: **54**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€134,88 | +€779,11 |
| 2 | Protegge +€30 dopo +€50 | -€137,68 | +€506,54 |
| 3 | Chiude 50% a +€50 | -€345,21 | +€299,02 |
| 4 | Protegge +€20 dopo +€50 | -€348,27 | +€295,96 |
| 5 | Take profit fisso +€100 | -€457,45 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€577,62 | +€66,61 |
| 7 | Strategia attuale | -€644,23 | €0,00 |
| 8 | Take profit fisso +€150 | -€644,23 | €0,00 |
| 9 | Take profit fisso +€200 | -€644,23 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€899,56 | -€255,33 |
| 11 | Take profit fisso +€75 | -€1.407,30 | -€763,08 |
| 12 | TP +€50 / SL -€50 | -€2.148,34 | -€1.504,11 |
| 13 | Take profit fisso +€25 | -€2.825,40 | -€2.181,18 |
| 14 | Take profit fisso +€50 | -€2.943,44 | -€2.299,21 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
