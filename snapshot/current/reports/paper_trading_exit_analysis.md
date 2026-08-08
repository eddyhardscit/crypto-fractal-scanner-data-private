# Analisi uscite paper trading a leva

Generato: 2026-08-08T17:41:19+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3626**
- Trade con percorso cronologico utilizzabile: **3572**
- Trade che hanno raggiunto almeno +€50: **1408**
- Di questi, chiusi poi in perdita: **290**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.235,12 | +€11.996,14 |
| 2 | Chiude 50% a +€50 | -€3.519,02 | +€3.242,00 |
| 3 | Protegge +€30 dopo +€50 | -€5.021,32 | +€1.739,70 |
| 4 | TP +€50 / SL -€50 | -€5.434,53 | +€1.326,49 |
| 5 | Protegge +€20 dopo +€50 | -€5.947,61 | +€813,41 |
| 6 | Trailing 20% dopo +€50 | -€6.652,23 | +€108,79 |
| 7 | Strategia attuale | -€6.761,02 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.761,02 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.765,34 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.976,26 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.884,13 | -€1.123,10 |
| 12 | Take profit fisso +€75 | -€10.171,16 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.192,87 | -€10.431,85 |
| 14 | Take profit fisso +€50 | -€17.291,62 | -€10.530,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
