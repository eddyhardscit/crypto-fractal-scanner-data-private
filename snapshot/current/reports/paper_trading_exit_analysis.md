# Analisi uscite paper trading a leva

Generato: 2026-07-29T15:10:13+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3387**
- Trade con percorso cronologico utilizzabile: **3333**
- Trade che hanno raggiunto almeno +€50: **1381**
- Di questi, chiusi poi in perdita: **277**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.434,66 | +€11.979,04 |
| 2 | Chiude 50% a +€50 | -€3.790,38 | +€2.753,99 |
| 3 | Protegge +€30 dopo +€50 | -€5.188,99 | +€1.355,38 |
| 4 | Protegge +€20 dopo +€50 | -€5.971,81 | +€572,56 |
| 5 | TP +€50 / SL -€50 | -€6.059,75 | +€484,63 |
| 6 | Strategia attuale | -€6.544,37 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.544,37 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.548,69 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.759,61 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€7.049,58 | -€505,21 |
| 11 | Pareggio dopo +€50 | -€7.672,09 | -€1.127,72 |
| 12 | Take profit fisso +€75 | -€10.679,94 | -€4.135,56 |
| 13 | Take profit fisso +€50 | -€17.899,73 | -€11.355,36 |
| 14 | Take profit fisso +€25 | -€18.164,12 | -€11.619,75 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
