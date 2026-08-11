# Analisi uscite paper trading a leva

Generato: 2026-08-11T10:14:13+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3706**
- Trade con percorso cronologico utilizzabile: **3652**
- Trade che hanno raggiunto almeno +€50: **1443**
- Di questi, chiusi poi in perdita: **291**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.720,23 | +€12.384,42 |
| 2 | Chiude 50% a +€50 | -€3.082,90 | +€2.581,29 |
| 3 | Protegge +€30 dopo +€50 | -€3.893,37 | +€1.770,81 |
| 4 | Protegge +€20 dopo +€50 | -€4.829,67 | +€834,52 |
| 5 | TP +€50 / SL -€50 | -€5.362,10 | +€302,09 |
| 6 | Strategia attuale | -€5.664,19 | €0,00 |
| 7 | Take profit fisso +€200 | -€5.664,19 | €0,00 |
| 8 | Take profit fisso +€150 | -€5.668,50 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€5.872,99 | -€208,80 |
| 10 | Take profit fisso +€100 | -€6.023,13 | -€358,95 |
| 11 | Pareggio dopo +€50 | -€6.786,18 | -€1.121,99 |
| 12 | Take profit fisso +€75 | -€9.740,71 | -€4.076,52 |
| 13 | Take profit fisso +€50 | -€17.607,46 | -€11.943,28 |
| 14 | Take profit fisso +€25 | -€18.292,45 | -€12.628,26 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
