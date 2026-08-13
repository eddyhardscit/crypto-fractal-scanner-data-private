# Analisi uscite paper trading a leva

Generato: 2026-08-13T03:46:40+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4766**
- Trade con percorso cronologico utilizzabile: **4712**
- Trade che hanno raggiunto almeno +€50: **1780**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€6.245,08 | +€18.347,25 |
| 2 | TP +€50 / SL -€50 | -€18.330,03 | +€6.262,30 |
| 3 | Protegge +€30 dopo +€50 | -€20.036,67 | +€4.555,66 |
| 4 | Chiude 50% a +€50 | -€20.885,20 | +€3.707,13 |
| 5 | Protegge +€20 dopo +€50 | -€22.207,90 | +€2.384,43 |
| 6 | Strategia attuale | -€24.592,33 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.592,33 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.596,65 | -€4,32 |
| 9 | Take profit fisso +€100 | -€25.126,88 | -€534,55 |
| 10 | Trailing 20% dopo +€50 | -€25.349,17 | -€756,83 |
| 11 | Pareggio dopo +€50 | -€26.095,34 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€29.485,82 | -€4.893,49 |
| 13 | Take profit fisso +€50 | -€36.484,57 | -€11.892,24 |
| 14 | Take profit fisso +€25 | -€41.142,51 | -€16.550,18 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
