# Analisi uscite paper trading a leva

Generato: 2026-07-21T07:38:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **443**
- Trade con percorso cronologico utilizzabile: **389**
- Trade che hanno raggiunto almeno +€50: **185**
- Di questi, chiusi poi in perdita: **46**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€280,83 | +€577,97 |
| 2 | Protegge +€30 dopo +€50 | +€209,40 | +€506,54 |
| 3 | Protegge +€20 dopo +€50 | -€1,18 | +€295,96 |
| 4 | Chiude 50% a +€50 | -€191,18 | +€105,96 |
| 5 | Pareggio dopo +€50 | -€230,54 | +€66,61 |
| 6 | Take profit fisso +€100 | -€274,00 | +€23,14 |
| 7 | Strategia attuale | -€297,14 | €0,00 |
| 8 | Take profit fisso +€150 | -€297,14 | €0,00 |
| 9 | Take profit fisso +€200 | -€297,14 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€582,33 | -€285,19 |
| 11 | Take profit fisso +€75 | -€1.105,36 | -€808,22 |
| 12 | TP +€50 / SL -€50 | -€1.922,53 | -€1.625,39 |
| 13 | Take profit fisso +€50 | -€2.516,49 | -€2.219,35 |
| 14 | Take profit fisso +€25 | -€2.839,38 | -€2.542,24 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
