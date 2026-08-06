# Analisi uscite paper trading a leva

Generato: 2026-08-06T22:56:23+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3613**
- Trade con percorso cronologico utilizzabile: **3559**
- Trade che hanno raggiunto almeno +€50: **1407**
- Di questi, chiusi poi in perdita: **289**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.337,53 | +€11.995,61 |
| 2 | Chiude 50% a +€50 | -€3.466,35 | +€3.191,73 |
| 3 | Protegge +€30 dopo +€50 | -€4.918,38 | +€1.739,70 |
| 4 | TP +€50 / SL -€50 | -€5.332,13 | +€1.325,96 |
| 5 | Protegge +€20 dopo +€50 | -€5.844,68 | +€813,41 |
| 6 | Trailing 20% dopo +€50 | -€6.549,29 | +€108,79 |
| 7 | Strategia attuale | -€6.658,08 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.658,08 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.662,40 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.873,32 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.781,19 | -€1.123,10 |
| 12 | Take profit fisso +€75 | -€10.068,22 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.165,46 | -€10.507,38 |
| 14 | Take profit fisso +€50 | -€17.188,69 | -€10.530,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
