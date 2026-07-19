# Analisi uscite paper trading a leva

Generato: 2026-07-19T17:08:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **276**
- Trade con percorso cronologico utilizzabile: **222**
- Trade che hanno raggiunto almeno +€50: **118**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.950,98 | +€338,71 |
| 2 | Protegge +€20 dopo +€50 | +€1.818,71 | +€206,43 |
| 3 | Stop loss fisso -€50 | +€1.760,64 | +€148,36 |
| 4 | Take profit fisso +€100 | +€1.712,06 | +€99,78 |
| 5 | Pareggio dopo +€50 | +€1.650,82 | +€38,54 |
| 6 | Strategia attuale | +€1.612,28 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.612,28 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.612,28 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.413,86 | -€198,42 |
| 10 | Trailing 20% dopo +€50 | +€1.180,67 | -€431,60 |
| 11 | Take profit fisso +€75 | +€1.021,49 | -€590,79 |
| 12 | TP +€50 / SL -€50 | +€175,13 | -€1.437,15 |
| 13 | Take profit fisso +€50 | +€10,77 | -€1.601,50 |
| 14 | Take profit fisso +€25 | -€771,74 | -€2.384,02 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
