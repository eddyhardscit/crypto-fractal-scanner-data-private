# Analisi uscite paper trading a leva

Generato: 2026-07-27T13:23:32+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2489**
- Trade con percorso cronologico utilizzabile: **2435**
- Trade che hanno raggiunto almeno +€50: **1095**
- Di questi, chiusi poi in perdita: **200**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.836,65 | +€9.545,03 |
| 2 | Protegge +€30 dopo +€50 | +€1.729,46 | +€1.437,84 |
| 3 | Protegge +€20 dopo +€50 | +€966,27 | +€674,65 |
| 4 | Chiude 50% a +€50 | +€641,15 | +€349,53 |
| 5 | Trailing 20% dopo +€50 | +€448,64 | +€157,02 |
| 6 | Strategia attuale | +€291,62 | €0,00 |
| 7 | Take profit fisso +€200 | +€291,62 | €0,00 |
| 8 | Take profit fisso +€150 | +€287,31 | -€4,32 |
| 9 | Take profit fisso +€100 | +€207,43 | -€84,19 |
| 10 | Pareggio dopo +€50 | -€502,55 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€1.378,98 | -€1.670,60 |
| 12 | Take profit fisso +€75 | -€3.665,00 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€10.785,88 | -€11.077,50 |
| 14 | Take profit fisso +€25 | -€14.525,75 | -€14.817,37 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
