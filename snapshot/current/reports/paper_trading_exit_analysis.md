# Analisi uscite paper trading a leva

Generato: 2026-08-08T11:41:56+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3623**
- Trade con percorso cronologico utilizzabile: **3569**
- Trade che hanno raggiunto almeno +€50: **1408**
- Di questi, chiusi poi in perdita: **290**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.253,85 | +€11.996,14 |
| 2 | Chiude 50% a +€50 | -€3.500,29 | +€3.242,00 |
| 3 | Protegge +€30 dopo +€50 | -€5.002,59 | +€1.739,70 |
| 4 | TP +€50 / SL -€50 | -€5.415,80 | +€1.326,49 |
| 5 | Protegge +€20 dopo +€50 | -€5.928,88 | +€813,41 |
| 6 | Trailing 20% dopo +€50 | -€6.633,50 | +€108,79 |
| 7 | Strategia attuale | -€6.742,29 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.742,29 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.746,61 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.957,53 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.865,40 | -€1.123,10 |
| 12 | Take profit fisso +€75 | -€10.152,43 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.174,14 | -€10.431,85 |
| 14 | Take profit fisso +€50 | -€17.272,89 | -€10.530,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
