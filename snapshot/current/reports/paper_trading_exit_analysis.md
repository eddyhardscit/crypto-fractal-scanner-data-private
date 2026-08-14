# Analisi uscite paper trading a leva

Generato: 2026-08-14T06:13:05+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4934**
- Trade con percorso cronologico utilizzabile: **4880**
- Trade che hanno raggiunto almeno +€50: **1840**
- Di questi, chiusi poi in perdita: **351**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€5.294,53 | +€18.952,81 |
| 2 | TP +€50 / SL -€50 | -€17.307,99 | +€6.939,35 |
| 3 | Protegge +€30 dopo +€50 | -€19.460,48 | +€4.786,86 |
| 4 | Chiude 50% a +€50 | -€20.419,54 | +€3.827,80 |
| 5 | Protegge +€20 dopo +€50 | -€21.847,66 | +€2.399,69 |
| 6 | Strategia attuale | -€24.247,34 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.247,34 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.251,66 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€24.429,40 | -€182,06 |
| 10 | Take profit fisso +€100 | -€24.766,26 | -€518,92 |
| 11 | Pareggio dopo +€50 | -€25.746,96 | -€1.499,61 |
| 12 | Take profit fisso +€75 | -€29.262,08 | -€5.014,74 |
| 13 | Take profit fisso +€50 | -€36.068,09 | -€11.820,75 |
| 14 | Take profit fisso +€25 | -€41.548,19 | -€17.300,85 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
