# Analisi uscite paper trading a leva

Generato: 2026-08-13T09:18:05+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4793**
- Trade con percorso cronologico utilizzabile: **4739**
- Trade che hanno raggiunto almeno +€50: **1791**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€6.157,86 | +€18.376,74 |
| 2 | TP +€50 / SL -€50 | -€18.228,85 | +€6.305,75 |
| 3 | Protegge +€30 dopo +€50 | -€20.024,01 | +€4.510,59 |
| 4 | Chiude 50% a +€50 | -€20.783,99 | +€3.750,61 |
| 5 | Protegge +€20 dopo +€50 | -€22.255,24 | +€2.279,36 |
| 6 | Strategia attuale | -€24.534,60 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.534,60 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.538,92 | -€4,32 |
| 9 | Take profit fisso +€100 | -€25.069,15 | -€534,55 |
| 10 | Trailing 20% dopo +€50 | -€25.239,60 | -€705,00 |
| 11 | Pareggio dopo +€50 | -€26.037,61 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€29.455,31 | -€4.920,71 |
| 13 | Take profit fisso +€50 | -€36.412,87 | -€11.878,28 |
| 14 | Take profit fisso +€25 | -€41.272,82 | -€16.738,22 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
