# Analisi uscite paper trading a leva

Generato: 2026-07-26T15:54:20+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1969**
- Trade con percorso cronologico utilizzabile: **1915**
- Trade che hanno raggiunto almeno +€50: **889**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.914,36 | +€8.860,64 |
| 2 | Chiude 50% a +€50 | +€42,04 | +€988,32 |
| 3 | Protegge +€30 dopo +€50 | -€352,89 | +€593,39 |
| 4 | Protegge +€20 dopo +€50 | -€640,00 | +€306,28 |
| 5 | TP +€50 / SL -€50 | -€919,85 | +€26,43 |
| 6 | Strategia attuale | -€946,28 | €0,00 |
| 7 | Take profit fisso +€200 | -€946,28 | €0,00 |
| 8 | Take profit fisso +€150 | -€947,02 | -€0,74 |
| 9 | Take profit fisso +€100 | -€1.010,98 | -€64,70 |
| 10 | Trailing 20% dopo +€50 | -€1.514,98 | -€568,70 |
| 11 | Pareggio dopo +€50 | -€1.789,15 | -€842,87 |
| 12 | Take profit fisso +€75 | -€4.047,36 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€9.642,35 | -€8.696,08 |
| 14 | Take profit fisso +€25 | -€13.952,08 | -€13.005,80 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
