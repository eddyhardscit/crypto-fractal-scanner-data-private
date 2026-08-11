# Analisi uscite paper trading a leva

Generato: 2026-08-11T09:17:28+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3695**
- Trade con percorso cronologico utilizzabile: **3641**
- Trade che hanno raggiunto almeno +€50: **1439**
- Di questi, chiusi poi in perdita: **291**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.625,36 | +€12.346,43 |
| 2 | Chiude 50% a +€50 | -€3.041,91 | +€2.679,16 |
| 3 | Protegge +€30 dopo +€50 | -€3.950,25 | +€1.770,81 |
| 4 | Protegge +€20 dopo +€50 | -€4.886,55 | +€834,52 |
| 5 | TP +€50 / SL -€50 | -€5.261,23 | +€459,84 |
| 6 | Strategia attuale | -€5.721,07 | €0,00 |
| 7 | Take profit fisso +€200 | -€5.721,07 | €0,00 |
| 8 | Take profit fisso +€150 | -€5.725,38 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€5.763,85 | -€42,78 |
| 10 | Take profit fisso +€100 | -€6.077,66 | -€356,59 |
| 11 | Pareggio dopo +€50 | -€6.843,06 | -€1.121,99 |
| 12 | Take profit fisso +€75 | -€9.701,85 | -€3.980,79 |
| 13 | Take profit fisso +€50 | -€17.468,61 | -€11.747,54 |
| 14 | Take profit fisso +€25 | -€18.053,59 | -€12.332,53 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
