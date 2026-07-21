# Analisi uscite paper trading a leva

Generato: 2026-07-21T11:38:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **465**
- Trade con percorso cronologico utilizzabile: **411**
- Trade che hanno raggiunto almeno +€50: **198**
- Di questi, chiusi poi in perdita: **54**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€154,82 | +€779,11 |
| 2 | Protegge +€30 dopo +€50 | -€117,75 | +€506,54 |
| 3 | Chiude 50% a +€50 | -€325,27 | +€299,02 |
| 4 | Protegge +€20 dopo +€50 | -€328,33 | +€295,96 |
| 5 | Take profit fisso +€100 | -€437,52 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€557,68 | +€66,61 |
| 7 | Strategia attuale | -€624,29 | €0,00 |
| 8 | Take profit fisso +€150 | -€624,29 | €0,00 |
| 9 | Take profit fisso +€200 | -€624,29 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€879,62 | -€255,33 |
| 11 | Take profit fisso +€75 | -€1.387,37 | -€763,08 |
| 12 | TP +€50 / SL -€50 | -€2.128,40 | -€1.504,11 |
| 13 | Take profit fisso +€25 | -€2.805,47 | -€2.181,18 |
| 14 | Take profit fisso +€50 | -€2.923,50 | -€2.299,21 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
