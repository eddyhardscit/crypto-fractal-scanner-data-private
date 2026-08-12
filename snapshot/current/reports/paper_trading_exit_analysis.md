# Analisi uscite paper trading a leva

Generato: 2026-08-12T10:29:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4401**
- Trade con percorso cronologico utilizzabile: **4347**
- Trade che hanno raggiunto almeno +€50: **1651**
- Di questi, chiusi poi in perdita: **324**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.561,85 | +€16.060,78 |
| 2 | TP +€50 / SL -€50 | -€14.969,37 | +€5.653,25 |
| 3 | Chiude 50% a +€50 | -€16.452,37 | +€4.170,26 |
| 4 | Protegge +€30 dopo +€50 | -€16.923,34 | +€3.699,29 |
| 5 | Protegge +€20 dopo +€50 | -€18.838,05 | +€1.784,57 |
| 6 | Strategia attuale | -€20.622,62 | €0,00 |
| 7 | Take profit fisso +€200 | -€20.622,62 | €0,00 |
| 8 | Take profit fisso +€150 | -€20.626,94 | -€4,32 |
| 9 | Take profit fisso +€100 | -€20.967,14 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€21.748,80 | -€1.126,17 |
| 11 | Pareggio dopo +€50 | -€22.345,49 | -€1.722,86 |
| 12 | Take profit fisso +€75 | -€24.338,61 | -€3.715,98 |
| 13 | Take profit fisso +€50 | -€30.837,44 | -€10.214,81 |
| 14 | Take profit fisso +€25 | -€33.246,75 | -€12.624,12 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
