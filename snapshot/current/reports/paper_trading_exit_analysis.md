# Analisi uscite paper trading a leva

Generato: 2026-07-24T23:09:11+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1239**
- Trade con percorso cronologico utilizzabile: **1185**
- Trade che hanno raggiunto almeno +€50: **565**
- Di questi, chiusi poi in perdita: **132**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€1.375,68 | +€2.751,27 |
| 2 | Chiude 50% a +€50 | +€10,50 | +€1.386,09 |
| 3 | Take profit fisso +€100 | -€1.087,60 | +€287,99 |
| 4 | Strategia attuale | -€1.375,59 | €0,00 |
| 5 | Take profit fisso +€150 | -€1.375,59 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.375,59 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€1.480,54 | -€104,96 |
| 8 | Protegge +€20 dopo +€50 | -€1.807,47 | -€431,89 |
| 9 | Take profit fisso +€75 | -€2.422,72 | -€1.047,13 |
| 10 | Pareggio dopo +€50 | -€2.549,13 | -€1.173,54 |
| 11 | Trailing 20% dopo +€50 | -€2.707,67 | -€1.332,08 |
| 12 | TP +€50 / SL -€50 | -€3.660,16 | -€2.284,58 |
| 13 | Take profit fisso +€50 | -€6.427,42 | -€5.051,84 |
| 14 | Take profit fisso +€25 | -€6.820,11 | -€5.444,52 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
