# Analisi uscite paper trading a leva

Generato: 2026-07-21T16:53:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **536**
- Trade con percorso cronologico utilizzabile: **482**
- Trade che hanno raggiunto almeno +€50: **226**
- Di questi, chiusi poi in perdita: **60**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€296,36 | +€882,62 |
| 2 | Protegge +€30 dopo +€50 | -€649,18 | +€529,80 |
| 3 | Chiude 50% a +€50 | -€820,86 | +€358,12 |
| 4 | Protegge +€20 dopo +€50 | -€889,77 | +€289,21 |
| 5 | Take profit fisso +€100 | -€992,21 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€1.112,38 | +€66,61 |
| 7 | Strategia attuale | -€1.178,98 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.178,98 | €0,00 |
| 9 | Take profit fisso +€200 | -€1.178,98 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€1.605,10 | -€426,12 |
| 11 | Take profit fisso +€75 | -€1.792,40 | -€613,42 |
| 12 | TP +€50 / SL -€50 | -€2.788,49 | -€1.609,50 |
| 13 | Take profit fisso +€50 | -€3.687,10 | -€2.508,12 |
| 14 | Take profit fisso +€25 | -€3.912,46 | -€2.733,48 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
