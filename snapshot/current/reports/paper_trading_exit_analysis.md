# Analisi uscite paper trading a leva

Generato: 2026-08-03T08:41:06+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3562**
- Trade con percorso cronologico utilizzabile: **3508**
- Trade che hanno raggiunto almeno +€50: **1406**
- Di questi, chiusi poi in perdita: **288**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.409,52 | +€11.995,61 |
| 2 | Chiude 50% a +€50 | -€3.420,03 | +€3.166,06 |
| 3 | Protegge +€30 dopo +€50 | -€4.877,74 | +€1.708,35 |
| 4 | TP +€50 / SL -€50 | -€5.311,48 | +€1.274,61 |
| 5 | Protegge +€20 dopo +€50 | -€5.794,03 | +€792,06 |
| 6 | Trailing 20% dopo +€50 | -€6.513,97 | +€72,11 |
| 7 | Strategia attuale | -€6.586,09 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.586,09 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.590,40 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.801,32 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.710,54 | -€1.124,45 |
| 12 | Take profit fisso +€75 | -€9.996,22 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.119,82 | -€10.533,73 |
| 14 | Take profit fisso +€50 | -€17.168,04 | -€10.581,95 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
