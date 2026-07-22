# Analisi uscite paper trading a leva

Generato: 2026-07-22T14:23:47+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **739**
- Trade con percorso cronologico utilizzabile: **685**
- Trade che hanno raggiunto almeno +€50: **283**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.200,39 | +€1.429,38 |
| 2 | Protegge +€30 dopo +€50 | -€3.102,21 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€3.299,55 | +€330,22 |
| 4 | Take profit fisso +€100 | -€3.435,81 | +€193,95 |
| 5 | Pareggio dopo +€50 | -€3.562,16 | +€67,61 |
| 6 | Chiude 50% a +€50 | -€3.607,05 | +€22,71 |
| 7 | Strategia attuale | -€3.629,77 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.629,77 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.629,77 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.089,08 | -€459,31 |
| 11 | Take profit fisso +€75 | -€4.268,02 | -€638,25 |
| 12 | TP +€50 / SL -€50 | -€5.607,88 | -€1.978,12 |
| 13 | Take profit fisso +€25 | -€6.190,72 | -€2.560,95 |
| 14 | Take profit fisso +€50 | -€7.053,26 | -€3.423,49 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
