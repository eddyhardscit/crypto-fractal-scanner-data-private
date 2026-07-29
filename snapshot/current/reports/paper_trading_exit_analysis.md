# Analisi uscite paper trading a leva

Generato: 2026-07-29T01:56:32+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3293**
- Trade con percorso cronologico utilizzabile: **3239**
- Trade che hanno raggiunto almeno +€50: **1338**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.482,27 | +€11.849,86 |
| 2 | Chiude 50% a +€50 | -€4.029,41 | +€2.338,18 |
| 3 | Protegge +€30 dopo +€50 | -€5.094,78 | +€1.272,81 |
| 4 | Protegge +€20 dopo +€50 | -€5.898,50 | +€469,09 |
| 5 | TP +€50 / SL -€50 | -€5.931,93 | +€435,66 |
| 6 | Strategia attuale | -€6.367,59 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.367,59 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.371,91 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€6.478,82 | -€111,23 |
| 10 | Take profit fisso +€100 | -€6.574,62 | -€207,03 |
| 11 | Pareggio dopo +€50 | -€7.547,61 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€10.608,32 | -€4.240,73 |
| 13 | Take profit fisso +€50 | -€17.643,66 | -€11.276,07 |
| 14 | Take profit fisso +€25 | -€18.214,57 | -€11.846,98 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
