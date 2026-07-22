# Analisi uscite paper trading a leva

Generato: 2026-07-22T00:53:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **613**
- Trade con percorso cronologico utilizzabile: **559**
- Trade che hanno raggiunto almeno +€50: **256**
- Di questi, chiusi poi in perdita: **62**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€18,62 | +€988,84 |
| 2 | Protegge +€30 dopo +€50 | -€379,42 | +€590,80 |
| 3 | Protegge +€20 dopo +€50 | -€640,00 | +€330,22 |
| 4 | Chiude 50% a +€50 | -€695,56 | +€274,66 |
| 5 | Take profit fisso +€100 | -€783,85 | +€186,37 |
| 6 | Pareggio dopo +€50 | -€902,61 | +€67,61 |
| 7 | Strategia attuale | -€970,22 | €0,00 |
| 8 | Take profit fisso +€150 | -€970,22 | €0,00 |
| 9 | Take profit fisso +€200 | -€970,22 | €0,00 |
| 10 | Take profit fisso +€75 | -€1.368,66 | -€398,44 |
| 11 | Trailing 20% dopo +€50 | -€1.376,04 | -€405,82 |
| 12 | TP +€50 / SL -€50 | -€2.689,79 | -€1.719,57 |
| 13 | Take profit fisso +€25 | -€3.651,17 | -€2.680,95 |
| 14 | Take profit fisso +€50 | -€3.694,63 | -€2.724,41 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
