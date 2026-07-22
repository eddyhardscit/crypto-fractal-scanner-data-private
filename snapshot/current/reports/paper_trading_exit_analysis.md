# Analisi uscite paper trading a leva

Generato: 2026-07-22T20:23:47+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **810**
- Trade con percorso cronologico utilizzabile: **756**
- Trade che hanno raggiunto almeno +€50: **319**
- Di questi, chiusi poi in perdita: **75**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.422,57 | +€1.553,87 |
| 2 | Protegge +€30 dopo +€50 | -€3.469,89 | +€506,54 |
| 3 | Chiude 50% a +€50 | -€3.650,21 | +€326,22 |
| 4 | Protegge +€20 dopo +€50 | -€3.693,33 | +€283,11 |
| 5 | Take profit fisso +€100 | -€3.782,48 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€3.908,83 | +€67,61 |
| 7 | Strategia attuale | -€3.976,44 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.976,44 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.976,44 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.438,19 | -€461,75 |
| 11 | Take profit fisso +€75 | -€4.631,65 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€6.098,81 | -€2.122,37 |
| 13 | Take profit fisso +€25 | -€6.598,20 | -€2.621,76 |
| 14 | Take profit fisso +€50 | -€7.668,67 | -€3.692,23 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
