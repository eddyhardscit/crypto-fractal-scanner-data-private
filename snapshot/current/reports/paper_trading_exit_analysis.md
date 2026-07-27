# Analisi uscite paper trading a leva

Generato: 2026-07-27T11:09:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2445**
- Trade con percorso cronologico utilizzabile: **2391**
- Trade che hanno raggiunto almeno +€50: **1084**
- Di questi, chiusi poi in perdita: **200**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€10.893,14 | +€9.483,88 |
| 2 | Protegge +€30 dopo +€50 | +€2.822,99 | +€1.413,73 |
| 3 | Protegge +€20 dopo +€50 | +€2.069,81 | +€660,55 |
| 4 | Chiude 50% a +€50 | +€1.529,77 | +€120,51 |
| 5 | Trailing 20% dopo +€50 | +€1.527,49 | +€118,23 |
| 6 | Strategia attuale | +€1.409,26 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.409,26 | €0,00 |
| 8 | Take profit fisso +€150 | +€1.404,94 | -€4,32 |
| 9 | Take profit fisso +€100 | +€1.325,07 | -€84,19 |
| 10 | Pareggio dopo +€50 | +€615,08 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€366,59 | -€1.775,85 |
| 12 | Take profit fisso +€75 | -€2.547,36 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€9.712,34 | -€11.121,60 |
| 14 | Take profit fisso +€25 | -€13.591,15 | -€15.000,40 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
