# Analisi uscite paper trading a leva

Generato: 2026-07-27T09:10:01+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2323**
- Trade con percorso cronologico utilizzabile: **2269**
- Trade che hanno raggiunto almeno +€50: **1076**
- Di questi, chiusi poi in perdita: **198**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€14.634,83 | +€9.163,83 |
| 2 | Protegge +€30 dopo +€50 | +€6.858,56 | +€1.387,57 |
| 3 | Protegge +€20 dopo +€50 | +€6.131,54 | +€660,55 |
| 4 | Trailing 20% dopo +€50 | +€5.495,34 | +€24,34 |
| 5 | Chiude 50% a +€50 | +€5.475,30 | +€4,31 |
| 6 | Strategia attuale | +€5.471,00 | €0,00 |
| 7 | Take profit fisso +€200 | +€5.471,00 | €0,00 |
| 8 | Take profit fisso +€150 | +€5.466,68 | -€4,32 |
| 9 | Take profit fisso +€100 | +€5.386,80 | -€84,19 |
| 10 | Pareggio dopo +€50 | +€4.676,82 | -€794,18 |
| 11 | TP +€50 / SL -€50 | +€3.270,10 | -€2.200,90 |
| 12 | Take profit fisso +€75 | +€1.514,38 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€5.755,61 | -€11.226,60 |
| 14 | Take profit fisso +€25 | -€13.394,09 | -€18.865,09 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
