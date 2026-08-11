# Analisi uscite paper trading a leva

Generato: 2026-08-11T03:59:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3677**
- Trade con percorso cronologico utilizzabile: **3623**
- Trade che hanno raggiunto almeno +€50: **1424**
- Di questi, chiusi poi in perdita: **291**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.578,34 | +€12.333,21 |
| 2 | Chiude 50% a +€50 | -€3.852,20 | +€2.902,67 |
| 3 | Protegge +€30 dopo +€50 | -€4.984,06 | +€1.770,81 |
| 4 | TP +€50 / SL -€50 | -€5.769,97 | +€984,90 |
| 5 | Protegge +€20 dopo +€50 | -€5.920,35 | +€834,52 |
| 6 | Trailing 20% dopo +€50 | -€6.600,70 | +€154,16 |
| 7 | Strategia attuale | -€6.754,87 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.754,87 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.759,19 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.986,31 | -€231,44 |
| 11 | Pareggio dopo +€50 | -€7.876,86 | -€1.121,99 |
| 12 | Take profit fisso +€75 | -€10.519,78 | -€3.764,91 |
| 13 | Take profit fisso +€50 | -€17.964,13 | -€11.209,26 |
| 14 | Take profit fisso +€25 | -€18.265,38 | -€11.510,51 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
