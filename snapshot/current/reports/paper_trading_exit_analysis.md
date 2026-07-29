# Analisi uscite paper trading a leva

Generato: 2026-07-29T19:10:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3399**
- Trade con percorso cronologico utilizzabile: **3345**
- Trade che hanno raggiunto almeno +€50: **1381**
- Di questi, chiusi poi in perdita: **277**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.176,79 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€4.063,70 | +€2.753,99 |
| 3 | Protegge +€30 dopo +€50 | -€5.462,31 | +€1.355,38 |
| 4 | Protegge +€20 dopo +€50 | -€6.245,13 | +€572,56 |
| 5 | TP +€50 / SL -€50 | -€6.317,62 | +€500,07 |
| 6 | Strategia attuale | -€6.817,69 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.817,69 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.822,01 | -€4,32 |
| 9 | Take profit fisso +€100 | -€7.032,93 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€7.322,90 | -€505,21 |
| 11 | Pareggio dopo +€50 | -€7.945,41 | -€1.127,72 |
| 12 | Take profit fisso +€75 | -€10.953,26 | -€4.135,56 |
| 13 | Take profit fisso +€25 | -€18.048,83 | -€11.231,14 |
| 14 | Take profit fisso +€50 | -€18.173,05 | -€11.355,36 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
