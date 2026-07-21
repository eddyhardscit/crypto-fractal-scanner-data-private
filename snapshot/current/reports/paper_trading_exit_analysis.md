# Analisi uscite paper trading a leva

Generato: 2026-07-21T06:38:42+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **442**
- Trade con percorso cronologico utilizzabile: **388**
- Trade che hanno raggiunto almeno +€50: **185**
- Di questi, chiusi poi in perdita: **46**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€330,83 | +€577,15 |
| 2 | Protegge +€30 dopo +€50 | +€260,22 | +€506,54 |
| 3 | Protegge +€20 dopo +€50 | +€49,64 | +€295,96 |
| 4 | Chiude 50% a +€50 | -€140,36 | +€105,96 |
| 5 | Pareggio dopo +€50 | -€179,72 | +€66,61 |
| 6 | Take profit fisso +€100 | -€223,18 | +€23,14 |
| 7 | Strategia attuale | -€246,32 | €0,00 |
| 8 | Take profit fisso +€150 | -€246,32 | €0,00 |
| 9 | Take profit fisso +€200 | -€246,32 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€531,51 | -€285,19 |
| 11 | Take profit fisso +€75 | -€1.054,54 | -€808,22 |
| 12 | TP +€50 / SL -€50 | -€1.872,53 | -€1.626,21 |
| 13 | Take profit fisso +€50 | -€2.465,67 | -€2.219,35 |
| 14 | Take profit fisso +€25 | -€2.788,56 | -€2.542,24 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
