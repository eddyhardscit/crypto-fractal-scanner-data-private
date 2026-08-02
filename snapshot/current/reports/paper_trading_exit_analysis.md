# Analisi uscite paper trading a leva

Generato: 2026-08-02T12:11:04+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3537**
- Trade con percorso cronologico utilizzabile: **3483**
- Trade che hanno raggiunto almeno +€50: **1402**
- Di questi, chiusi poi in perdita: **287**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.358,02 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.519,60 | +€3.116,87 |
| 3 | Protegge +€30 dopo +€50 | -€4.980,28 | +€1.656,18 |
| 4 | TP +€50 / SL -€50 | -€5.461,36 | +€1.175,10 |
| 5 | Protegge +€20 dopo +€50 | -€5.876,58 | +€759,89 |
| 6 | Trailing 20% dopo +€50 | -€6.559,40 | +€77,07 |
| 7 | Strategia attuale | -€6.636,46 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.636,46 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.640,78 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.851,70 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.753,09 | -€1.116,62 |
| 12 | Take profit fisso +€75 | -€10.169,24 | -€3.532,78 |
| 13 | Take profit fisso +€25 | -€17.270,43 | -€10.633,97 |
| 14 | Take profit fisso +€50 | -€17.316,80 | -€10.680,33 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
