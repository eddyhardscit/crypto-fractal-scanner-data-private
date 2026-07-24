# Analisi uscite paper trading a leva

Generato: 2026-07-24T20:09:04+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1209**
- Trade con percorso cronologico utilizzabile: **1155**
- Trade che hanno raggiunto almeno +€50: **546**
- Di questi, chiusi poi in perdita: **131**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€141,00 | +€2.745,21 |
| 2 | Chiude 50% a +€50 | -€1.190,36 | +€1.695,84 |
| 3 | Take profit fisso +€100 | -€2.539,87 | +€346,34 |
| 4 | Protegge +€30 dopo +€50 | -€2.590,48 | +€295,72 |
| 5 | Protegge +€20 dopo +€50 | -€2.857,41 | +€28,79 |
| 6 | Strategia attuale | -€2.886,21 | €0,00 |
| 7 | Take profit fisso +€150 | -€2.886,21 | €0,00 |
| 8 | Take profit fisso +€200 | -€2.886,21 | €0,00 |
| 9 | Trailing 20% dopo +€50 | -€3.527,18 | -€640,98 |
| 10 | Take profit fisso +€75 | -€3.552,63 | -€666,43 |
| 11 | Pareggio dopo +€50 | -€3.676,07 | -€789,87 |
| 12 | TP +€50 / SL -€50 | -€4.436,75 | -€1.550,55 |
| 13 | Take profit fisso +€50 | -€7.197,95 | -€4.311,74 |
| 14 | Take profit fisso +€25 | -€7.463,74 | -€4.577,53 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
