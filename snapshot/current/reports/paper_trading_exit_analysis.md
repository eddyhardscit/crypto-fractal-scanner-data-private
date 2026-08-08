# Analisi uscite paper trading a leva

Generato: 2026-08-08T22:41:09+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3632**
- Trade con percorso cronologico utilizzabile: **3578**
- Trade che hanno raggiunto almeno +€50: **1408**
- Di questi, chiusi poi in perdita: **290**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.233,59 | +€11.996,14 |
| 2 | Chiude 50% a +€50 | -€3.520,56 | +€3.242,00 |
| 3 | Protegge +€30 dopo +€50 | -€5.022,86 | +€1.739,70 |
| 4 | TP +€50 / SL -€50 | -€5.436,07 | +€1.326,49 |
| 5 | Protegge +€20 dopo +€50 | -€5.949,15 | +€813,41 |
| 6 | Trailing 20% dopo +€50 | -€6.653,76 | +€108,79 |
| 7 | Strategia attuale | -€6.762,55 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.762,55 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.766,87 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.977,79 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.885,66 | -€1.123,10 |
| 12 | Take profit fisso +€75 | -€10.172,69 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.194,40 | -€10.431,85 |
| 14 | Take profit fisso +€50 | -€17.293,16 | -€10.530,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
