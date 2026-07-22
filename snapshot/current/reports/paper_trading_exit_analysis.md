# Analisi uscite paper trading a leva

Generato: 2026-07-22T02:53:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **617**
- Trade con percorso cronologico utilizzabile: **563**
- Trade che hanno raggiunto almeno +€50: **257**
- Di questi, chiusi poi in perdita: **62**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€84,49 | +€988,84 |
| 2 | Protegge +€30 dopo +€50 | -€313,55 | +€590,80 |
| 3 | Protegge +€20 dopo +€50 | -€574,14 | +€330,22 |
| 4 | Chiude 50% a +€50 | -€631,08 | +€273,28 |
| 5 | Take profit fisso +€100 | -€717,98 | +€186,37 |
| 6 | Pareggio dopo +€50 | -€836,75 | +€67,61 |
| 7 | Strategia attuale | -€904,36 | €0,00 |
| 8 | Take profit fisso +€150 | -€904,36 | €0,00 |
| 9 | Take profit fisso +€200 | -€904,36 | €0,00 |
| 10 | Take profit fisso +€75 | -€1.302,80 | -€398,44 |
| 11 | Trailing 20% dopo +€50 | -€1.310,18 | -€405,82 |
| 12 | TP +€50 / SL -€50 | -€2.626,69 | -€1.722,34 |
| 13 | Take profit fisso +€25 | -€3.613,07 | -€2.708,72 |
| 14 | Take profit fisso +€50 | -€3.631,53 | -€2.727,17 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
