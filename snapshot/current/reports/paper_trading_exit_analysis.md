# Analisi uscite paper trading a leva

Generato: 2026-07-19T23:53:40+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **290**
- Trade con percorso cronologico utilizzabile: **236**
- Trade che hanno raggiunto almeno +€50: **124**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.096,47 | +€338,71 |
| 2 | Protegge +€20 dopo +€50 | +€1.964,20 | +€206,43 |
| 3 | Stop loss fisso -€50 | +€1.934,02 | +€176,25 |
| 4 | Take profit fisso +€100 | +€1.846,26 | +€88,50 |
| 5 | Pareggio dopo +€50 | +€1.796,31 | +€38,54 |
| 6 | Strategia attuale | +€1.757,77 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.757,77 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.757,77 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.445,59 | -€312,18 |
| 10 | Trailing 20% dopo +€50 | +€1.326,16 | -€431,60 |
| 11 | Take profit fisso +€75 | +€1.083,37 | -€674,39 |
| 12 | TP +€50 / SL -€50 | +€120,99 | -€1.636,77 |
| 13 | Take profit fisso +€50 | -€71,25 | -€1.829,02 |
| 14 | Take profit fisso +€25 | -€580,77 | -€2.338,54 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
