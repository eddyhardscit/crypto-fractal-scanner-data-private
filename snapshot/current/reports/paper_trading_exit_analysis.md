# Analisi uscite paper trading a leva

Generato: 2026-07-22T08:08:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **703**
- Trade con percorso cronologico utilizzabile: **649**
- Trade che hanno raggiunto almeno +€50: **278**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.723,39 | +€1.258,06 |
| 2 | Protegge +€30 dopo +€50 | -€2.453,89 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€2.651,23 | +€330,22 |
| 4 | Take profit fisso +€100 | -€2.800,57 | +€180,88 |
| 5 | Chiude 50% a +€50 | -€2.875,91 | +€105,54 |
| 6 | Pareggio dopo +€50 | -€2.913,84 | +€67,61 |
| 7 | Strategia attuale | -€2.981,45 | €0,00 |
| 8 | Take profit fisso +€150 | -€2.981,45 | €0,00 |
| 9 | Take profit fisso +€200 | -€2.981,45 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€3.459,04 | -€477,59 |
| 11 | Take profit fisso +€75 | -€3.535,31 | -€553,86 |
| 12 | TP +€50 / SL -€50 | -€4.965,23 | -€1.983,78 |
| 13 | Take profit fisso +€25 | -€5.652,77 | -€2.671,32 |
| 14 | Take profit fisso +€50 | -€6.239,28 | -€3.257,83 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
