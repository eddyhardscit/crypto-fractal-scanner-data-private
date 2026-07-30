# Analisi uscite paper trading a leva

Generato: 2026-07-30T00:25:21+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3415**
- Trade con percorso cronologico utilizzabile: **3361**
- Trade che hanno raggiunto almeno +€50: **1391**
- Di questi, chiusi poi in perdita: **277**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.465,99 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.669,32 | +€2.859,17 |
| 3 | Protegge +€30 dopo +€50 | -€5.153,40 | +€1.375,08 |
| 4 | TP +€50 / SL -€50 | -€5.818,08 | +€710,41 |
| 5 | Protegge +€20 dopo +€50 | -€5.959,70 | +€568,79 |
| 6 | Strategia attuale | -€6.528,49 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.528,49 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.532,80 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.743,73 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.830,83 | -€302,34 |
| 11 | Pareggio dopo +€50 | -€7.656,21 | -€1.127,72 |
| 12 | Take profit fisso +€75 | -€10.623,18 | -€4.094,69 |
| 13 | Take profit fisso +€50 | -€17.673,51 | -€11.145,02 |
| 14 | Take profit fisso +€25 | -€17.771,21 | -€11.242,72 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
