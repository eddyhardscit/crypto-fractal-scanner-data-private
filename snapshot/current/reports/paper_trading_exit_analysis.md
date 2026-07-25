# Analisi uscite paper trading a leva

Generato: 2026-07-25T22:39:15+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1546**
- Trade con percorso cronologico utilizzabile: **1492**
- Trade che hanno raggiunto almeno +€50: **741**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.649,79 | +€4.054,54 |
| 2 | Chiude 50% a +€50 | +€4.482,10 | +€886,85 |
| 3 | Protegge +€20 dopo +€50 | +€3.639,60 | +€44,35 |
| 4 | Strategia attuale | +€3.595,25 | €0,00 |
| 5 | Take profit fisso +€200 | +€3.595,25 | €0,00 |
| 6 | Take profit fisso +€150 | +€3.594,51 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€3.569,03 | -€26,22 |
| 8 | Take profit fisso +€100 | +€3.558,62 | -€36,63 |
| 9 | Pareggio dopo +€50 | +€2.714,41 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€2.096,22 | -€1.499,03 |
| 11 | Take profit fisso +€75 | +€1.044,56 | -€2.550,69 |
| 12 | TP +€50 / SL -€50 | -€565,44 | -€4.160,69 |
| 13 | Take profit fisso +€50 | -€4.481,84 | -€8.077,10 |
| 14 | Take profit fisso +€25 | -€7.209,11 | -€10.804,37 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
