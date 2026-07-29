# Analisi uscite paper trading a leva

Generato: 2026-07-29T00:55:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3292**
- Trade con percorso cronologico utilizzabile: **3238**
- Trade che hanno raggiunto almeno +€50: **1338**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.532,27 | +€11.793,44 |
| 2 | Chiude 50% a +€50 | -€3.922,98 | +€2.338,18 |
| 3 | Protegge +€30 dopo +€50 | -€4.988,35 | +€1.272,81 |
| 4 | Protegge +€20 dopo +€50 | -€5.792,08 | +€469,09 |
| 5 | TP +€50 / SL -€50 | -€5.881,93 | +€379,23 |
| 6 | Strategia attuale | -€6.261,16 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.261,16 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.265,48 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€6.372,40 | -€111,23 |
| 10 | Take profit fisso +€100 | -€6.468,20 | -€207,03 |
| 11 | Pareggio dopo +€50 | -€7.441,19 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€10.501,90 | -€4.240,73 |
| 13 | Take profit fisso +€50 | -€17.537,24 | -€11.276,07 |
| 14 | Take profit fisso +€25 | -€18.108,15 | -€11.846,98 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
