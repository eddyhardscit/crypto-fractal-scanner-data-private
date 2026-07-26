# Analisi uscite paper trading a leva

Generato: 2026-07-26T14:54:21+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1967**
- Trade con percorso cronologico utilizzabile: **1913**
- Trade che hanno raggiunto almeno +€50: **889**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.014,36 | +€8.853,23 |
| 2 | Chiude 50% a +€50 | +€149,45 | +€988,32 |
| 3 | Protegge +€30 dopo +€50 | -€245,49 | +€593,39 |
| 4 | Protegge +€20 dopo +€50 | -€532,60 | +€306,28 |
| 5 | TP +€50 / SL -€50 | -€819,85 | +€19,02 |
| 6 | Strategia attuale | -€838,87 | €0,00 |
| 7 | Take profit fisso +€200 | -€838,87 | €0,00 |
| 8 | Take profit fisso +€150 | -€839,61 | -€0,74 |
| 9 | Take profit fisso +€100 | -€903,58 | -€64,70 |
| 10 | Trailing 20% dopo +€50 | -€1.407,57 | -€568,70 |
| 11 | Pareggio dopo +€50 | -€1.681,74 | -€842,87 |
| 12 | Take profit fisso +€75 | -€3.939,95 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€9.534,95 | -€8.696,08 |
| 14 | Take profit fisso +€25 | -€14.002,08 | -€13.163,21 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
