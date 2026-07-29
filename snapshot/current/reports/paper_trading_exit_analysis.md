# Analisi uscite paper trading a leva

Generato: 2026-07-29T18:10:12+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3390**
- Trade con percorso cronologico utilizzabile: **3336**
- Trade che hanno raggiunto almeno +€50: **1381**
- Di questi, chiusi poi in perdita: **277**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.432,04 | +€11.979,04 |
| 2 | Chiude 50% a +€50 | -€3.793,00 | +€2.753,99 |
| 3 | Protegge +€30 dopo +€50 | -€5.191,62 | +€1.355,38 |
| 4 | Protegge +€20 dopo +€50 | -€5.974,44 | +€572,56 |
| 5 | TP +€50 / SL -€50 | -€6.062,37 | +€484,63 |
| 6 | Strategia attuale | -€6.547,00 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.547,00 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.551,31 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.762,24 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€7.052,21 | -€505,21 |
| 11 | Pareggio dopo +€50 | -€7.674,72 | -€1.127,72 |
| 12 | Take profit fisso +€75 | -€10.682,56 | -€4.135,56 |
| 13 | Take profit fisso +€50 | -€17.902,36 | -€11.355,36 |
| 14 | Take profit fisso +€25 | -€18.089,12 | -€11.542,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
