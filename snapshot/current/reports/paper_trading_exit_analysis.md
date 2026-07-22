# Analisi uscite paper trading a leva

Generato: 2026-07-22T16:23:48+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **751**
- Trade con percorso cronologico utilizzabile: **697**
- Trade che hanno raggiunto almeno +€50: **292**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.714,87 | +€1.439,11 |
| 2 | Protegge +€30 dopo +€50 | -€2.666,77 | +€487,20 |
| 3 | Protegge +€20 dopo +€50 | -€2.874,12 | +€279,86 |
| 4 | Take profit fisso +€100 | -€2.960,02 | +€193,95 |
| 5 | Pareggio dopo +€50 | -€3.086,37 | +€67,61 |
| 6 | Strategia attuale | -€3.153,97 | €0,00 |
| 7 | Take profit fisso +€150 | -€3.153,97 | €0,00 |
| 8 | Take profit fisso +€200 | -€3.153,97 | €0,00 |
| 9 | Chiude 50% a +€50 | -€3.201,35 | -€47,37 |
| 10 | Trailing 20% dopo +€50 | -€3.656,36 | -€502,38 |
| 11 | Take profit fisso +€75 | -€3.809,19 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€5.306,40 | -€2.152,43 |
| 13 | Take profit fisso +€25 | -€6.080,10 | -€2.926,12 |
| 14 | Take profit fisso +€50 | -€6.761,50 | -€3.607,53 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
