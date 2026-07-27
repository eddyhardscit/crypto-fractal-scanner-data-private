# Analisi uscite paper trading a leva

Generato: 2026-07-27T14:24:41+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2518**
- Trade con percorso cronologico utilizzabile: **2464**
- Trade che hanno raggiunto almeno +€50: **1101**
- Di questi, chiusi poi in perdita: **200**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.741,86 | +€9.554,81 |
| 2 | Protegge +€30 dopo +€50 | +€1.629,63 | +€1.442,58 |
| 3 | Protegge +€20 dopo +€50 | +€861,71 | +€674,65 |
| 4 | Chiude 50% a +€50 | +€644,66 | +€457,60 |
| 5 | Trailing 20% dopo +€50 | +€345,71 | +€158,65 |
| 6 | Strategia attuale | +€187,06 | €0,00 |
| 7 | Take profit fisso +€200 | +€187,06 | €0,00 |
| 8 | Take profit fisso +€150 | +€182,74 | -€4,32 |
| 9 | Take profit fisso +€100 | +€102,86 | -€84,19 |
| 10 | Pareggio dopo +€50 | -€607,12 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€1.449,02 | -€1.636,08 |
| 12 | Take profit fisso +€75 | -€3.769,56 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€10.865,70 | -€11.052,76 |
| 14 | Take profit fisso +€25 | -€14.487,48 | -€14.674,54 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
