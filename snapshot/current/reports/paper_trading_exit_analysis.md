# Analisi uscite paper trading a leva

Generato: 2026-07-20T08:23:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **348**
- Trade con percorso cronologico utilizzabile: **294**
- Trade che hanno raggiunto almeno +€50: **155**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.693,68 | +€433,98 |
| 2 | Stop loss fisso -€50 | +€1.535,86 | +€276,16 |
| 3 | Protegge +€20 dopo +€50 | +€1.513,10 | +€253,39 |
| 4 | Chiude 50% a +€50 | +€1.366,36 | +€106,65 |
| 5 | Take profit fisso +€100 | +€1.332,10 | +€72,39 |
| 6 | Pareggio dopo +€50 | +€1.326,10 | +€66,40 |
| 7 | Strategia attuale | +€1.259,71 | €0,00 |
| 8 | Take profit fisso +€150 | +€1.259,71 | €0,00 |
| 9 | Take profit fisso +€200 | +€1.259,71 | €0,00 |
| 10 | Trailing 20% dopo +€50 | +€865,27 | -€394,44 |
| 11 | Take profit fisso +€75 | +€655,76 | -€603,94 |
| 12 | TP +€50 / SL -€50 | -€145,58 | -€1.405,29 |
| 13 | Take profit fisso +€50 | -€437,73 | -€1.697,44 |
| 14 | Take profit fisso +€25 | -€782,29 | -€2.041,99 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
