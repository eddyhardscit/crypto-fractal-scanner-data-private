# Analisi uscite paper trading a leva

Generato: 2026-07-21T20:53:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **576**
- Trade con percorso cronologico utilizzabile: **522**
- Trade che hanno raggiunto almeno +€50: **252**
- Di questi, chiusi poi in perdita: **62**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€978,88 | +€894,36 |
| 2 | Protegge +€30 dopo +€50 | +€675,32 | +€590,80 |
| 3 | Protegge +€20 dopo +€50 | +€414,73 | +€330,22 |
| 4 | Chiude 50% a +€50 | +€367,55 | +€283,04 |
| 5 | Take profit fisso +€100 | +€270,89 | +€186,37 |
| 6 | Pareggio dopo +€50 | +€152,12 | +€67,61 |
| 7 | Strategia attuale | +€84,52 | €0,00 |
| 8 | Take profit fisso +€150 | +€84,52 | €0,00 |
| 9 | Take profit fisso +€200 | +€84,52 | €0,00 |
| 10 | Take profit fisso +€75 | -€397,17 | -€481,68 |
| 11 | Trailing 20% dopo +€50 | -€397,42 | -€481,94 |
| 12 | TP +€50 / SL -€50 | -€1.712,78 | -€1.797,30 |
| 13 | Take profit fisso +€50 | -€2.623,14 | -€2.707,65 |
| 14 | Take profit fisso +€25 | -€3.114,12 | -€3.198,63 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
