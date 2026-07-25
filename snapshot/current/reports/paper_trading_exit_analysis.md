# Analisi uscite paper trading a leva

Generato: 2026-07-25T06:09:20+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1306**
- Trade con percorso cronologico utilizzabile: **1252**
- Trade che hanno raggiunto almeno +€50: **608**
- Di questi, chiusi poi in perdita: **142**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€2.597,78 | +€3.115,85 |
| 2 | Chiude 50% a +€50 | +€886,68 | +€1.404,76 |
| 3 | Take profit fisso +€100 | -€256,09 | +€261,99 |
| 4 | Strategia attuale | -€518,08 | €0,00 |
| 5 | Take profit fisso +€150 | -€518,08 | €0,00 |
| 6 | Take profit fisso +€200 | -€518,08 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€853,99 | -€335,92 |
| 8 | Protegge +€20 dopo +€50 | -€962,30 | -€444,22 |
| 9 | Take profit fisso +€75 | -€1.595,70 | -€1.077,62 |
| 10 | Pareggio dopo +€50 | -€1.637,95 | -€1.119,88 |
| 11 | Trailing 20% dopo +€50 | -€1.989,42 | -€1.471,34 |
| 12 | TP +€50 / SL -€50 | -€2.987,31 | -€2.469,23 |
| 13 | Take profit fisso +€50 | -€6.116,24 | -€5.598,16 |
| 14 | Take profit fisso +€25 | -€7.134,17 | -€6.616,09 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
