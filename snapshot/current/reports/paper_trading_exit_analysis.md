# Analisi uscite paper trading a leva

Generato: 2026-07-22T23:23:50+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **812**
- Trade con percorso cronologico utilizzabile: **758**
- Trade che hanno raggiunto almeno +€50: **319**
- Di questi, chiusi poi in perdita: **75**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.522,57 | +€1.554,77 |
| 2 | Protegge +€30 dopo +€50 | -€3.570,80 | +€506,54 |
| 3 | Chiude 50% a +€50 | -€3.751,12 | +€326,22 |
| 4 | Protegge +€20 dopo +€50 | -€3.794,23 | +€283,11 |
| 5 | Take profit fisso +€100 | -€3.883,39 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€4.009,73 | +€67,61 |
| 7 | Strategia attuale | -€4.077,34 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.077,34 | €0,00 |
| 9 | Take profit fisso +€200 | -€4.077,34 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.539,10 | -€461,75 |
| 11 | Take profit fisso +€75 | -€4.732,56 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€6.198,81 | -€2.121,47 |
| 13 | Take profit fisso +€25 | -€6.699,11 | -€2.621,76 |
| 14 | Take profit fisso +€50 | -€7.769,57 | -€3.692,23 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
