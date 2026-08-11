# Analisi uscite paper trading a leva

Generato: 2026-08-11T13:15:01+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3748**
- Trade con percorso cronologico utilizzabile: **3694**
- Trade che hanno raggiunto almeno +€50: **1467**
- Di questi, chiusi poi in perdita: **291**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.017,28 | +€12.399,67 |
| 2 | Chiude 50% a +€50 | -€1.929,00 | +€2.453,40 |
| 3 | Protegge +€30 dopo +€50 | -€2.537,85 | +€1.844,55 |
| 4 | Protegge +€20 dopo +€50 | -€3.514,14 | +€868,26 |
| 5 | TP +€50 / SL -€50 | -€4.320,83 | +€61,56 |
| 6 | Strategia attuale | -€4.382,40 | €0,00 |
| 7 | Take profit fisso +€200 | -€4.382,40 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.386,72 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€4.624,10 | -€241,71 |
| 10 | Take profit fisso +€100 | -€4.809,71 | -€427,31 |
| 11 | Pareggio dopo +€50 | -€5.504,39 | -€1.121,99 |
| 12 | Take profit fisso +€75 | -€8.650,39 | -€4.267,99 |
| 13 | Take profit fisso +€50 | -€16.581,46 | -€12.199,06 |
| 14 | Take profit fisso +€25 | -€17.849,53 | -€13.467,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
