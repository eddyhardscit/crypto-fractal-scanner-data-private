# Analisi uscite paper trading a leva

Generato: 2026-07-22T17:23:48+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **767**
- Trade con percorso cronologico utilizzabile: **713**
- Trade che hanno raggiunto almeno +€50: **301**
- Di questi, chiusi poi in perdita: **67**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.356,45 | +€1.449,28 |
| 2 | Protegge +€30 dopo +€50 | -€2.318,53 | +€487,20 |
| 3 | Protegge +€20 dopo +€50 | -€2.525,87 | +€279,86 |
| 4 | Take profit fisso +€100 | -€2.611,77 | +€193,95 |
| 5 | Pareggio dopo +€50 | -€2.738,12 | +€67,61 |
| 6 | Strategia attuale | -€2.805,73 | €0,00 |
| 7 | Take profit fisso +€150 | -€2.805,73 | €0,00 |
| 8 | Take profit fisso +€200 | -€2.805,73 | €0,00 |
| 9 | Chiude 50% a +€50 | -€2.860,95 | -€55,22 |
| 10 | Trailing 20% dopo +€50 | -€3.308,11 | -€502,38 |
| 11 | Take profit fisso +€75 | -€3.460,95 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€5.071,71 | -€2.265,99 |
| 13 | Take profit fisso +€25 | -€5.926,89 | -€3.121,16 |
| 14 | Take profit fisso +€50 | -€6.536,99 | -€3.731,26 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
