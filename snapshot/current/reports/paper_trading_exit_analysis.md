# Analisi uscite paper trading a leva

Generato: 2026-07-26T03:39:07+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1616**
- Trade con percorso cronologico utilizzabile: **1562**
- Trade che hanno raggiunto almeno +€50: **775**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.657,05 | +€4.322,76 |
| 2 | Chiude 50% a +€50 | +€4.744,23 | +€409,93 |
| 3 | Protegge +€20 dopo +€50 | +€4.378,64 | +€44,35 |
| 4 | Strategia attuale | +€4.334,30 | €0,00 |
| 5 | Take profit fisso +€200 | +€4.334,30 | €0,00 |
| 6 | Take profit fisso +€150 | +€4.333,56 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€4.308,08 | -€26,22 |
| 8 | Take profit fisso +€100 | +€4.297,03 | -€37,27 |
| 9 | Pareggio dopo +€50 | +€3.453,46 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€2.842,58 | -€1.491,72 |
| 11 | Take profit fisso +€75 | +€1.573,85 | -€2.760,45 |
| 12 | TP +€50 / SL -€50 | -€512,01 | -€4.846,31 |
| 13 | Take profit fisso +€50 | -€4.696,64 | -€9.030,94 |
| 14 | Take profit fisso +€25 | -€7.913,52 | -€12.247,82 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
