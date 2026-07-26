# Analisi uscite paper trading a leva

Generato: 2026-07-26T08:39:15+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1836**
- Trade con percorso cronologico utilizzabile: **1782**
- Trade che hanno raggiunto almeno +€50: **869**
- Di questi, chiusi poi in perdita: **182**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€10.491,34 | +€8.703,18 |
| 2 | Chiude 50% a +€50 | +€2.570,58 | +€782,42 |
| 3 | Protegge +€30 dopo +€50 | +€2.295,66 | +€507,50 |
| 4 | Protegge +€20 dopo +€50 | +€2.115,24 | +€327,08 |
| 5 | Strategia attuale | +€1.788,16 | €0,00 |
| 6 | Take profit fisso +€200 | +€1.788,16 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.787,42 | -€0,74 |
| 8 | Take profit fisso +€100 | +€1.723,46 | -€64,70 |
| 9 | TP +€50 / SL -€50 | +€1.347,27 | -€440,89 |
| 10 | Trailing 20% dopo +€50 | +€997,59 | -€790,56 |
| 11 | Pareggio dopo +€50 | +€931,89 | -€856,27 |
| 12 | Take profit fisso +€75 | -€1.310,42 | -€3.098,57 |
| 13 | Take profit fisso +€50 | -€7.217,78 | -€9.005,94 |
| 14 | Take profit fisso +€25 | -€11.561,63 | -€13.349,79 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
