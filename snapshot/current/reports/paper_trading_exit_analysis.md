# Analisi uscite paper trading a leva

Generato: 2026-08-06T12:56:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3604**
- Trade con percorso cronologico utilizzabile: **3550**
- Trade che hanno raggiunto almeno +€50: **1407**
- Di questi, chiusi poi in perdita: **289**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.320,65 | +€11.995,61 |
| 2 | Chiude 50% a +€50 | -€3.483,23 | +€3.191,73 |
| 3 | Protegge +€30 dopo +€50 | -€4.935,26 | +€1.739,70 |
| 4 | TP +€50 / SL -€50 | -€5.349,01 | +€1.325,96 |
| 5 | Protegge +€20 dopo +€50 | -€5.861,55 | +€813,41 |
| 6 | Trailing 20% dopo +€50 | -€6.566,17 | +€108,79 |
| 7 | Strategia attuale | -€6.674,96 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.674,96 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.679,28 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.890,20 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.798,07 | -€1.123,10 |
| 12 | Take profit fisso +€75 | -€10.085,10 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.182,34 | -€10.507,38 |
| 14 | Take profit fisso +€50 | -€17.205,56 | -€10.530,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
