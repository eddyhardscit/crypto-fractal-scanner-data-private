# Analisi uscite paper trading a leva

Generato: 2026-08-02T09:12:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3535**
- Trade con percorso cronologico utilizzabile: **3481**
- Trade che hanno raggiunto almeno +€50: **1402**
- Di questi, chiusi poi in perdita: **287**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.354,01 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.523,61 | +€3.116,87 |
| 3 | Protegge +€30 dopo +€50 | -€4.984,29 | +€1.656,18 |
| 4 | TP +€50 / SL -€50 | -€5.465,37 | +€1.175,10 |
| 5 | Protegge +€20 dopo +€50 | -€5.880,59 | +€759,89 |
| 6 | Trailing 20% dopo +€50 | -€6.563,41 | +€77,07 |
| 7 | Strategia attuale | -€6.640,47 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.640,47 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.644,79 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.855,71 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.757,10 | -€1.116,62 |
| 12 | Take profit fisso +€75 | -€10.173,25 | -€3.532,78 |
| 13 | Take profit fisso +€25 | -€17.274,44 | -€10.633,97 |
| 14 | Take profit fisso +€50 | -€17.320,81 | -€10.680,33 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
