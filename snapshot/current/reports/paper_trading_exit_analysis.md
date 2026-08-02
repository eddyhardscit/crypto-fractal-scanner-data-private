# Analisi uscite paper trading a leva

Generato: 2026-08-02T23:41:00+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3555**
- Trade con percorso cronologico utilizzabile: **3501**
- Trade che hanno raggiunto almeno +€50: **1405**
- Di questi, chiusi poi in perdita: **288**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.421,50 | +€11.995,61 |
| 2 | Chiude 50% a +€50 | -€3.428,77 | +€3.145,34 |
| 3 | Protegge +€30 dopo +€50 | -€4.887,19 | +€1.686,91 |
| 4 | TP +€50 / SL -€50 | -€5.340,94 | +€1.233,17 |
| 5 | Protegge +€20 dopo +€50 | -€5.793,49 | +€780,62 |
| 6 | Trailing 20% dopo +€50 | -€6.492,95 | +€81,16 |
| 7 | Strategia attuale | -€6.574,11 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.574,11 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.578,42 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.789,35 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.690,00 | -€1.115,89 |
| 12 | Take profit fisso +€75 | -€10.050,68 | -€3.476,57 |
| 13 | Take profit fisso +€25 | -€17.150,00 | -€10.575,89 |
| 14 | Take profit fisso +€50 | -€17.197,49 | -€10.623,39 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
