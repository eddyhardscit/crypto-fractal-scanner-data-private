# Analisi uscite paper trading a leva

Generato: 2026-07-23T16:38:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **919**
- Trade con percorso cronologico utilizzabile: **865**
- Trade che hanno raggiunto almeno +€50: **376**
- Di questi, chiusi poi in perdita: **81**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€656,74 | +€1.700,96 |
| 2 | Take profit fisso +€100 | -€2.188,12 | +€169,58 |
| 3 | Strategia attuale | -€2.357,70 | €0,00 |
| 4 | Take profit fisso +€150 | -€2.357,70 | €0,00 |
| 5 | Take profit fisso +€200 | -€2.357,70 | €0,00 |
| 6 | Chiude 50% a +€50 | -€2.404,77 | -€47,07 |
| 7 | Protegge +€20 dopo +€50 | -€2.762,13 | -€404,43 |
| 8 | Protegge +€30 dopo +€50 | -€2.791,64 | -€433,94 |
| 9 | Pareggio dopo +€50 | -€3.216,76 | -€859,06 |
| 10 | Take profit fisso +€75 | -€3.217,57 | -€859,87 |
| 11 | Trailing 20% dopo +€50 | -€3.901,02 | -€1.543,32 |
| 12 | TP +€50 / SL -€50 | -€5.484,13 | -€3.126,43 |
| 13 | Take profit fisso +€25 | -€6.516,62 | -€4.158,92 |
| 14 | Take profit fisso +€50 | -€7.201,08 | -€4.843,38 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
