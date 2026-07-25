# Analisi uscite paper trading a leva

Generato: 2026-07-25T16:24:06+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1449**
- Trade con percorso cronologico utilizzabile: **1395**
- Trade che hanno raggiunto almeno +€50: **705**
- Di questi, chiusi poi in perdita: **145**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.281,95 | +€3.275,45 |
| 2 | Strategia attuale | +€6.006,50 | €0,00 |
| 3 | Take profit fisso +€200 | +€6.006,50 | €0,00 |
| 4 | Take profit fisso +€150 | +€6.005,76 | -€0,74 |
| 5 | Take profit fisso +€100 | +€5.969,87 | -€36,63 |
| 6 | Chiude 50% a +€50 | +€5.784,18 | -€222,32 |
| 7 | Protegge +€20 dopo +€50 | +€5.600,74 | -€405,76 |
| 8 | Protegge +€30 dopo +€50 | +€5.451,18 | -€555,32 |
| 9 | Pareggio dopo +€50 | +€4.887,37 | -€1.119,13 |
| 10 | Trailing 20% dopo +€50 | +€3.836,07 | -€2.170,43 |
| 11 | Take profit fisso +€75 | +€3.477,94 | -€2.528,56 |
| 12 | TP +€50 / SL -€50 | +€328,66 | -€5.677,84 |
| 13 | Take profit fisso +€50 | -€2.959,87 | -€8.966,36 |
| 14 | Take profit fisso +€25 | -€6.209,30 | -€12.215,80 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
