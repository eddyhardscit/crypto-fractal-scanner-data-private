# Analisi uscite paper trading a leva

Generato: 2026-08-13T04:45:50+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4777**
- Trade con percorso cronologico utilizzabile: **4723**
- Trade che hanno raggiunto almeno +€50: **1780**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€6.578,28 | +€18.373,80 |
| 2 | TP +€50 / SL -€50 | -€18.663,23 | +€6.288,85 |
| 3 | Protegge +€30 dopo +€50 | -€20.396,42 | +€4.555,66 |
| 4 | Chiude 50% a +€50 | -€21.244,95 | +€3.707,13 |
| 5 | Protegge +€20 dopo +€50 | -€22.567,65 | +€2.384,43 |
| 6 | Strategia attuale | -€24.952,08 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.952,08 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.956,40 | -€4,32 |
| 9 | Take profit fisso +€100 | -€25.486,64 | -€534,55 |
| 10 | Trailing 20% dopo +€50 | -€25.708,92 | -€756,83 |
| 11 | Pareggio dopo +€50 | -€26.455,09 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€29.845,57 | -€4.893,49 |
| 13 | Take profit fisso +€50 | -€36.844,32 | -€11.892,24 |
| 14 | Take profit fisso +€25 | -€41.502,26 | -€16.550,18 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
