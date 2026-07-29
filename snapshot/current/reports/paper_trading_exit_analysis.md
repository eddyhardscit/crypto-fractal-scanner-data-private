# Analisi uscite paper trading a leva

Generato: 2026-07-29T11:10:14+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3386**
- Trade con percorso cronologico utilizzabile: **3332**
- Trade che hanno raggiunto almeno +€50: **1380**
- Di questi, chiusi poi in perdita: **276**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.436,05 | +€11.979,04 |
| 2 | Chiude 50% a +€50 | -€3.814,69 | +€2.728,30 |
| 3 | Protegge +€30 dopo +€50 | -€5.218,99 | +€1.324,00 |
| 4 | Protegge +€20 dopo +€50 | -€5.991,81 | +€551,18 |
| 5 | TP +€50 / SL -€50 | -€6.109,75 | +€433,24 |
| 6 | Strategia attuale | -€6.542,99 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.542,99 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.547,31 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.758,23 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€7.099,38 | -€556,39 |
| 11 | Pareggio dopo +€50 | -€7.672,09 | -€1.129,10 |
| 12 | Take profit fisso +€75 | -€10.754,94 | -€4.211,95 |
| 13 | Take profit fisso +€50 | -€17.949,73 | -€11.406,74 |
| 14 | Take profit fisso +€25 | -€18.189,12 | -€11.646,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
