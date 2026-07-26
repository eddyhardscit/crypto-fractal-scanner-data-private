# Analisi uscite paper trading a leva

Generato: 2026-07-26T02:39:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1608**
- Trade con percorso cronologico utilizzabile: **1554**
- Trade che hanno raggiunto almeno +€50: **775**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.004,51 | +€4.292,81 |
| 2 | Chiude 50% a +€50 | +€5.121,63 | +€409,93 |
| 3 | Protegge +€20 dopo +€50 | +€4.756,05 | +€44,35 |
| 4 | Strategia attuale | +€4.711,70 | €0,00 |
| 5 | Take profit fisso +€200 | +€4.711,70 | €0,00 |
| 6 | Take profit fisso +€150 | +€4.710,96 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€4.685,48 | -€26,22 |
| 8 | Take profit fisso +€100 | +€4.674,43 | -€37,27 |
| 9 | Pareggio dopo +€50 | +€3.830,86 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€3.219,98 | -€1.491,72 |
| 11 | Take profit fisso +€75 | +€1.951,25 | -€2.760,45 |
| 12 | TP +€50 / SL -€50 | -€164,56 | -€4.876,26 |
| 13 | Take profit fisso +€50 | -€4.319,24 | -€9.030,94 |
| 14 | Take profit fisso +€25 | -€7.536,12 | -€12.247,82 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
