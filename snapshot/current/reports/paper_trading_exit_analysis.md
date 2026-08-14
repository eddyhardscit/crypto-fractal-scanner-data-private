# Analisi uscite paper trading a leva

Generato: 2026-08-14T02:12:04+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4870**
- Trade con percorso cronologico utilizzabile: **4816**
- Trade che hanno raggiunto almeno +€50: **1810**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€5.315,19 | +€18.546,71 |
| 2 | TP +€50 / SL -€50 | -€17.846,45 | +€6.015,45 |
| 3 | Protegge +€30 dopo +€50 | -€19.351,31 | +€4.510,59 |
| 4 | Chiude 50% a +€50 | -€20.341,43 | +€3.520,47 |
| 5 | Protegge +€20 dopo +€50 | -€21.582,54 | +€2.279,36 |
| 6 | Strategia attuale | -€23.861,90 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.861,90 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.866,21 | -€4,32 |
| 9 | Take profit fisso +€100 | -€24.416,68 | -€554,78 |
| 10 | Trailing 20% dopo +€50 | -€24.538,24 | -€676,34 |
| 11 | Pareggio dopo +€50 | -€25.364,91 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.947,48 | -€5.085,58 |
| 13 | Take profit fisso +€50 | -€36.200,45 | -€12.338,55 |
| 14 | Take profit fisso +€25 | -€41.027,41 | -€17.165,51 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
