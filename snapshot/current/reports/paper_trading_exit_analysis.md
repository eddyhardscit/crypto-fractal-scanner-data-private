# Analisi uscite paper trading a leva

Generato: 2026-07-24T14:53:57+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1126**
- Trade con percorso cronologico utilizzabile: **1072**
- Trade che hanno raggiunto almeno +€50: **493**
- Di questi, chiusi poi in perdita: **116**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€835,95 | +€2.374,96 |
| 2 | Chiude 50% a +€50 | -€2.021,24 | +€1.189,67 |
| 3 | Take profit fisso +€100 | -€2.853,78 | +€357,12 |
| 4 | Protegge +€30 dopo +€50 | -€3.199,57 | +€11,34 |
| 5 | Strategia attuale | -€3.210,91 | €0,00 |
| 6 | Take profit fisso +€150 | -€3.210,91 | €0,00 |
| 7 | Take profit fisso +€200 | -€3.210,91 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€3.376,50 | -€165,59 |
| 9 | Take profit fisso +€75 | -€3.816,45 | -€605,55 |
| 10 | Pareggio dopo +€50 | -€4.116,29 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€4.256,93 | -€1.046,02 |
| 12 | TP +€50 / SL -€50 | -€5.278,28 | -€2.067,38 |
| 13 | Take profit fisso +€25 | -€7.483,18 | -€4.272,27 |
| 14 | Take profit fisso +€50 | -€7.669,23 | -€4.458,33 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
