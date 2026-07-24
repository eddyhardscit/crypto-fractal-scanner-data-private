# Analisi uscite paper trading a leva

Generato: 2026-07-24T12:53:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1099**
- Trade con percorso cronologico utilizzabile: **1045**
- Trade che hanno raggiunto almeno +€50: **477**
- Di questi, chiusi poi in perdita: **114**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€965,26 | +€2.339,55 |
| 2 | Chiude 50% a +€50 | -€2.231,74 | +€1.073,07 |
| 3 | Take profit fisso +€100 | -€3.214,57 | +€90,24 |
| 4 | Protegge +€30 dopo +€50 | -€3.294,43 | +€10,38 |
| 5 | Strategia attuale | -€3.304,81 | €0,00 |
| 6 | Take profit fisso +€150 | -€3.304,81 | €0,00 |
| 7 | Take profit fisso +€200 | -€3.304,81 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€3.470,40 | -€165,59 |
| 9 | Take profit fisso +€75 | -€4.120,42 | -€815,61 |
| 10 | Pareggio dopo +€50 | -€4.210,20 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€4.242,24 | -€937,42 |
| 12 | TP +€50 / SL -€50 | -€5.442,15 | -€2.137,34 |
| 13 | Take profit fisso +€25 | -€7.604,56 | -€4.299,75 |
| 14 | Take profit fisso +€50 | -€7.797,69 | -€4.492,88 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
