# Analisi uscite paper trading a leva

Generato: 2026-08-05T14:29:02+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3595**
- Trade con percorso cronologico utilizzabile: **3541**
- Trade che hanno raggiunto almeno +€50: **1407**
- Di questi, chiusi poi in perdita: **289**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.363,18 | +€11.995,61 |
| 2 | Chiude 50% a +€50 | -€3.440,69 | +€3.191,73 |
| 3 | Protegge +€30 dopo +€50 | -€4.892,73 | +€1.739,70 |
| 4 | TP +€50 / SL -€50 | -€5.306,47 | +€1.325,96 |
| 5 | Protegge +€20 dopo +€50 | -€5.819,02 | +€813,41 |
| 6 | Trailing 20% dopo +€50 | -€6.523,64 | +€108,79 |
| 7 | Strategia attuale | -€6.632,43 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.632,43 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.636,74 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.847,67 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.755,53 | -€1.123,10 |
| 12 | Take profit fisso +€75 | -€10.042,56 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.139,81 | -€10.507,38 |
| 14 | Take profit fisso +€50 | -€17.163,03 | -€10.530,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
