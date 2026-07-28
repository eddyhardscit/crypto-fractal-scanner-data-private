# Analisi uscite paper trading a leva

Generato: 2026-07-28T16:40:27+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3177**
- Trade con percorso cronologico utilizzabile: **3123**
- Trade che hanno raggiunto almeno +€50: **1320**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.286,92 | +€11.301,65 |
| 2 | Chiude 50% a +€50 | -€705,63 | +€2.309,10 |
| 3 | Protegge +€30 dopo +€50 | -€1.799,73 | +€1.215,00 |
| 4 | Protegge +€20 dopo +€50 | -€2.563,45 | +€451,28 |
| 5 | Strategia attuale | -€3.014,73 | €0,00 |
| 6 | Take profit fisso +€200 | -€3.014,73 | €0,00 |
| 7 | Take profit fisso +€150 | -€3.019,05 | -€4,32 |
| 8 | TP +€50 / SL -€50 | -€3.037,66 | -€22,93 |
| 9 | Take profit fisso +€100 | -€3.221,76 | -€207,03 |
| 10 | Trailing 20% dopo +€50 | -€3.294,54 | -€279,81 |
| 11 | Pareggio dopo +€50 | -€4.194,75 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€7.524,98 | -€4.510,25 |
| 13 | Take profit fisso +€50 | -€14.201,18 | -€11.186,45 |
| 14 | Take profit fisso +€25 | -€14.633,87 | -€11.619,14 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
