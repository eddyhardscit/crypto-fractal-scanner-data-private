# Analisi uscite paper trading a leva

Generato: 2026-08-13T10:17:17+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4798**
- Trade con percorso cronologico utilizzabile: **4744**
- Trade che hanno raggiunto almeno +€50: **1791**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€6.123,38 | +€18.376,74 |
| 2 | TP +€50 / SL -€50 | -€18.194,37 | +€6.305,75 |
| 3 | Protegge +€30 dopo +€50 | -€19.989,53 | +€4.510,59 |
| 4 | Chiude 50% a +€50 | -€20.749,52 | +€3.750,61 |
| 5 | Protegge +€20 dopo +€50 | -€22.220,77 | +€2.279,36 |
| 6 | Strategia attuale | -€24.500,12 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.500,12 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.504,44 | -€4,32 |
| 9 | Take profit fisso +€100 | -€25.034,68 | -€534,55 |
| 10 | Trailing 20% dopo +€50 | -€25.205,12 | -€705,00 |
| 11 | Pareggio dopo +€50 | -€26.003,13 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€29.420,84 | -€4.920,71 |
| 13 | Take profit fisso +€50 | -€36.378,40 | -€11.878,28 |
| 14 | Take profit fisso +€25 | -€41.242,56 | -€16.742,44 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
