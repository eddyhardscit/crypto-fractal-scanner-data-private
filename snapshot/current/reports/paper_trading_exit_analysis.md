# Analisi uscite paper trading a leva

Generato: 2026-07-22T19:23:49+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **808**
- Trade con percorso cronologico utilizzabile: **754**
- Trade che hanno raggiunto almeno +€50: **319**
- Di questi, chiusi poi in perdita: **75**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.322,57 | +€1.547,72 |
| 2 | Protegge +€30 dopo +€50 | -€3.363,74 | +€506,54 |
| 3 | Chiude 50% a +€50 | -€3.544,06 | +€326,22 |
| 4 | Protegge +€20 dopo +€50 | -€3.587,18 | +€283,11 |
| 5 | Take profit fisso +€100 | -€3.676,33 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€3.802,68 | +€67,61 |
| 7 | Strategia attuale | -€3.870,29 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.870,29 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.870,29 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.332,04 | -€461,75 |
| 11 | Take profit fisso +€75 | -€4.525,51 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€5.998,81 | -€2.128,52 |
| 13 | Take profit fisso +€25 | -€6.492,05 | -€2.621,76 |
| 14 | Take profit fisso +€50 | -€7.562,52 | -€3.692,23 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
