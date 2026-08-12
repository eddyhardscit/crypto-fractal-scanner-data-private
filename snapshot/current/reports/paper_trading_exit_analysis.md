# Analisi uscite paper trading a leva

Generato: 2026-08-12T07:29:05+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4382**
- Trade con percorso cronologico utilizzabile: **4328**
- Trade che hanno raggiunto almeno +€50: **1650**
- Di questi, chiusi poi in perdita: **324**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€3.909,62 | +€16.031,84 |
| 2 | TP +€50 / SL -€50 | -€14.357,81 | +€5.583,64 |
| 3 | Chiude 50% a +€50 | -€15.791,54 | +€4.149,92 |
| 4 | Protegge +€30 dopo +€50 | -€16.262,84 | +€3.678,61 |
| 5 | Protegge +€20 dopo +€50 | -€18.167,55 | +€1.773,90 |
| 6 | Strategia attuale | -€19.941,46 | €0,00 |
| 7 | Take profit fisso +€200 | -€19.941,46 | €0,00 |
| 8 | Take profit fisso +€150 | -€19.945,77 | -€4,32 |
| 9 | Take profit fisso +€100 | -€20.285,97 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€21.097,15 | -€1.155,70 |
| 11 | Pareggio dopo +€50 | -€21.664,32 | -€1.722,86 |
| 12 | Take profit fisso +€75 | -€23.657,44 | -€3.715,98 |
| 13 | Take profit fisso +€50 | -€30.196,94 | -€10.255,49 |
| 14 | Take profit fisso +€25 | -€32.718,72 | -€12.777,27 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
