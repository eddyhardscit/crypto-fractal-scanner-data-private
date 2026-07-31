# Analisi uscite paper trading a leva

Generato: 2026-07-31T09:25:27+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3443**
- Trade con percorso cronologico utilizzabile: **3389**
- Trade che hanno raggiunto almeno +€50: **1395**
- Di questi, chiusi poi in perdita: **280**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.467,08 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.590,70 | +€2.936,70 |
| 3 | Protegge +€30 dopo +€50 | -€5.091,55 | +€1.435,85 |
| 4 | TP +€50 / SL -€50 | -€5.712,63 | +€814,77 |
| 5 | Protegge +€20 dopo +€50 | -€5.917,84 | +€609,56 |
| 6 | Strategia attuale | -€6.527,40 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.527,40 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.531,71 | -€4,32 |
| 9 | Take profit fisso +€100 | -€6.742,64 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.779,99 | -€252,59 |
| 11 | Pareggio dopo +€50 | -€7.654,35 | -€1.126,95 |
| 12 | Take profit fisso +€75 | -€10.518,48 | -€3.991,08 |
| 13 | Take profit fisso +€50 | -€17.568,06 | -€11.040,66 |
| 14 | Take profit fisso +€25 | -€17.610,20 | -€11.082,80 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
