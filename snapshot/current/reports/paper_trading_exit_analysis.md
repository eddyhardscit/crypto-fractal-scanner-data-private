# Analisi uscite paper trading a leva

Generato: 2026-07-21T08:38:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **444**
- Trade con percorso cronologico utilizzabile: **390**
- Trade che hanno raggiunto almeno +€50: **186**
- Di questi, chiusi poi in perdita: **46**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€374,32 | +€577,97 |
| 2 | Protegge +€30 dopo +€50 | +€302,89 | +€506,54 |
| 3 | Protegge +€20 dopo +€50 | +€92,31 | +€295,96 |
| 4 | Chiude 50% a +€50 | -€119,44 | +€84,21 |
| 5 | Pareggio dopo +€50 | -€137,04 | +€66,61 |
| 6 | Take profit fisso +€100 | -€180,51 | +€23,14 |
| 7 | Strategia attuale | -€203,65 | €0,00 |
| 8 | Take profit fisso +€150 | -€203,65 | €0,00 |
| 9 | Take profit fisso +€200 | -€203,65 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€534,65 | -€331,01 |
| 11 | Take profit fisso +€75 | -€1.030,36 | -€826,71 |
| 12 | TP +€50 / SL -€50 | -€1.872,53 | -€1.668,88 |
| 13 | Take profit fisso +€50 | -€2.466,49 | -€2.262,84 |
| 14 | Take profit fisso +€25 | -€2.814,38 | -€2.610,73 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
