# Analisi uscite paper trading a leva

Generato: 2026-08-01T10:55:40+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3511**
- Trade con percorso cronologico utilizzabile: **3457**
- Trade che hanno raggiunto almeno +€50: **1402**
- Di questi, chiusi poi in perdita: **287**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.344,80 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.532,82 | +€3.116,87 |
| 3 | Protegge +€30 dopo +€50 | -€4.993,51 | +€1.656,18 |
| 4 | TP +€50 / SL -€50 | -€5.474,59 | +€1.175,10 |
| 5 | Protegge +€20 dopo +€50 | -€5.889,80 | +€759,89 |
| 6 | Trailing 20% dopo +€50 | -€6.572,62 | +€77,07 |
| 7 | Strategia attuale | -€6.649,69 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.649,69 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.654,00 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.864,92 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.766,31 | -€1.116,62 |
| 12 | Take profit fisso +€75 | -€10.182,47 | -€3.532,78 |
| 13 | Take profit fisso +€50 | -€17.330,02 | -€10.680,33 |
| 14 | Take profit fisso +€25 | -€17.363,13 | -€10.713,45 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
