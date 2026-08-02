# Analisi uscite paper trading a leva

Generato: 2026-08-02T20:26:06+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3545**
- Trade con percorso cronologico utilizzabile: **3491**
- Trade che hanno raggiunto almeno +€50: **1403**
- Di questi, chiusi poi in perdita: **288**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.380,38 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.471,86 | +€3.142,24 |
| 3 | Protegge +€30 dopo +€50 | -€4.927,19 | +€1.686,91 |
| 4 | TP +€50 / SL -€50 | -€5.388,27 | +€1.225,83 |
| 5 | Protegge +€20 dopo +€50 | -€5.833,48 | +€780,62 |
| 6 | Trailing 20% dopo +€50 | -€6.536,79 | +€77,31 |
| 7 | Strategia attuale | -€6.614,10 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.614,10 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.618,42 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.829,34 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.729,99 | -€1.115,89 |
| 12 | Take profit fisso +€75 | -€10.146,88 | -€3.532,78 |
| 13 | Take profit fisso +€25 | -€17.222,33 | -€10.608,23 |
| 14 | Take profit fisso +€50 | -€17.243,70 | -€10.629,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
