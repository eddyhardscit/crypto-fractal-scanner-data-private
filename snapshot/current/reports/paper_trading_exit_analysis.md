# Analisi uscite paper trading a leva

Generato: 2026-08-13T05:44:56+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4782**
- Trade con percorso cronologico utilizzabile: **4728**
- Trade che hanno raggiunto almeno +€50: **1782**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€6.445,49 | +€18.376,74 |
| 2 | TP +€50 / SL -€50 | -€18.604,02 | +€6.218,20 |
| 3 | Protegge +€30 dopo +€50 | -€20.380,15 | +€4.442,07 |
| 4 | Chiude 50% a +€50 | -€21.151,89 | +€3.670,33 |
| 5 | Protegge +€20 dopo +€50 | -€22.571,38 | +€2.250,84 |
| 6 | Strategia attuale | -€24.822,23 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.822,23 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.826,54 | -€4,32 |
| 9 | Take profit fisso +€100 | -€25.356,78 | -€534,55 |
| 10 | Trailing 20% dopo +€50 | -€25.679,06 | -€856,83 |
| 11 | Pareggio dopo +€50 | -€26.325,23 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€29.739,30 | -€4.917,08 |
| 13 | Take profit fisso +€50 | -€36.788,05 | -€11.965,83 |
| 14 | Take profit fisso +€25 | -€41.496,00 | -€16.673,77 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
