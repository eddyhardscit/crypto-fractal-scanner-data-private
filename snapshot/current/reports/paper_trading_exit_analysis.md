# Analisi uscite paper trading a leva

Generato: 2026-07-22T18:23:48+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **784**
- Trade con percorso cronologico utilizzabile: **730**
- Trade che hanno raggiunto almeno +€50: **314**
- Di questi, chiusi poi in perdita: **72**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.463,86 | +€1.458,84 |
| 2 | Protegge +€30 dopo +€50 | -€2.422,25 | +€500,46 |
| 3 | Protegge +€20 dopo +€50 | -€2.639,59 | +€283,11 |
| 4 | Chiude 50% a +€50 | -€2.675,83 | +€246,87 |
| 5 | Take profit fisso +€100 | -€2.728,75 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€2.855,09 | +€67,61 |
| 7 | Strategia attuale | -€2.922,70 | €0,00 |
| 8 | Take profit fisso +€150 | -€2.922,70 | €0,00 |
| 9 | Take profit fisso +€200 | -€2.922,70 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€3.408,98 | -€486,28 |
| 11 | Take profit fisso +€75 | -€3.577,92 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€5.145,87 | -€2.223,17 |
| 13 | Take profit fisso +€25 | -€5.736,45 | -€2.813,75 |
| 14 | Take profit fisso +€50 | -€6.620,71 | -€3.698,00 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
