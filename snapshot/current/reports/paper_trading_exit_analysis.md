# Analisi uscite paper trading a leva

Generato: 2026-07-25T21:39:20+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1540**
- Trade con percorso cronologico utilizzabile: **1486**
- Trade che hanno raggiunto almeno +€50: **741**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.641,51 | +€4.054,54 |
| 2 | Chiude 50% a +€50 | +€4.473,82 | +€886,85 |
| 3 | Protegge +€20 dopo +€50 | +€3.631,32 | +€44,35 |
| 4 | Strategia attuale | +€3.586,97 | €0,00 |
| 5 | Take profit fisso +€200 | +€3.586,97 | €0,00 |
| 6 | Take profit fisso +€150 | +€3.586,23 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€3.560,75 | -€26,22 |
| 8 | Take profit fisso +€100 | +€3.550,34 | -€36,63 |
| 9 | Pareggio dopo +€50 | +€2.706,13 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€2.087,94 | -€1.499,03 |
| 11 | Take profit fisso +€75 | +€1.036,28 | -€2.550,69 |
| 12 | TP +€50 / SL -€50 | -€573,72 | -€4.160,69 |
| 13 | Take profit fisso +€50 | -€4.490,13 | -€8.077,10 |
| 14 | Take profit fisso +€25 | -€7.217,40 | -€10.804,37 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
