# Analisi uscite paper trading a leva

Generato: 2026-07-27T15:24:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2576**
- Trade con percorso cronologico utilizzabile: **2522**
- Trade che hanno raggiunto almeno +€50: **1111**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.542,09 | +€9.616,38 |
| 2 | Protegge +€30 dopo +€50 | +€368,29 | +€1.442,58 |
| 3 | Chiude 50% a +€50 | -€362,64 | +€711,65 |
| 4 | Protegge +€20 dopo +€50 | -€399,64 | +€674,65 |
| 5 | Trailing 20% dopo +€50 | -€915,64 | +€158,65 |
| 6 | Strategia attuale | -€1.074,29 | €0,00 |
| 7 | Take profit fisso +€200 | -€1.074,29 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.078,60 | -€4,32 |
| 9 | Take profit fisso +€100 | -€1.158,48 | -€84,19 |
| 10 | Pareggio dopo +€50 | -€1.868,46 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€2.648,80 | -€1.574,51 |
| 12 | Take profit fisso +€75 | -€5.030,91 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€12.127,04 | -€11.052,76 |
| 14 | Take profit fisso +€25 | -€15.051,09 | -€13.976,81 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
