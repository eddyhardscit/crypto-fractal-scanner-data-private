# Analisi uscite paper trading a leva

Generato: 2026-07-20T02:08:37+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **303**
- Trade con percorso cronologico utilizzabile: **249**
- Trade che hanno raggiunto almeno +€50: **132**
- Di questi, chiusi poi in perdita: **30**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.062,08 | +€405,22 |
| 2 | Protegge +€20 dopo +€50 | +€1.909,81 | +€252,95 |
| 3 | Stop loss fisso -€50 | +€1.863,93 | +€207,07 |
| 4 | Take profit fisso +€100 | +€1.745,36 | +€88,50 |
| 5 | Pareggio dopo +€50 | +€1.712,93 | +€56,07 |
| 6 | Strategia attuale | +€1.656,86 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.656,86 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.656,86 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.501,06 | -€155,81 |
| 10 | Trailing 20% dopo +€50 | +€1.263,72 | -€393,14 |
| 11 | Take profit fisso +€75 | +€961,46 | -€695,41 |
| 12 | TP +€50 / SL -€50 | +€111,41 | -€1.545,46 |
| 13 | Take profit fisso +€50 | -€111,66 | -€1.768,52 |
| 14 | Take profit fisso +€25 | -€491,63 | -€2.148,50 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
