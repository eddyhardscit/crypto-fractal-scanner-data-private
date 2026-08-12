# Analisi uscite paper trading a leva

Generato: 2026-08-12T08:29:07+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4386**
- Trade con percorso cronologico utilizzabile: **4332**
- Trade che hanno raggiunto almeno +€50: **1650**
- Di questi, chiusi poi in perdita: **324**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.059,99 | +€16.045,60 |
| 2 | TP +€50 / SL -€50 | -€14.508,18 | +€5.597,40 |
| 3 | Chiude 50% a +€50 | -€15.955,66 | +€4.149,92 |
| 4 | Protegge +€30 dopo +€50 | -€16.426,97 | +€3.678,61 |
| 5 | Protegge +€20 dopo +€50 | -€18.331,68 | +€1.773,90 |
| 6 | Strategia attuale | -€20.105,58 | €0,00 |
| 7 | Take profit fisso +€200 | -€20.105,58 | €0,00 |
| 8 | Take profit fisso +€150 | -€20.109,90 | -€4,32 |
| 9 | Take profit fisso +€100 | -€20.450,10 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€21.261,28 | -€1.155,70 |
| 11 | Pareggio dopo +€50 | -€21.828,45 | -€1.722,86 |
| 12 | Take profit fisso +€75 | -€23.821,57 | -€3.715,98 |
| 13 | Take profit fisso +€50 | -€30.361,07 | -€10.255,49 |
| 14 | Take profit fisso +€25 | -€32.882,85 | -€12.777,27 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
