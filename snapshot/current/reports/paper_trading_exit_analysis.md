# Analisi uscite paper trading a leva

Generato: 2026-07-22T21:23:49+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **811**
- Trade con percorso cronologico utilizzabile: **757**
- Trade che hanno raggiunto almeno +€50: **319**
- Di questi, chiusi poi in perdita: **75**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.472,57 | +€1.554,58 |
| 2 | Protegge +€30 dopo +€50 | -€3.520,61 | +€506,54 |
| 3 | Chiude 50% a +€50 | -€3.700,93 | +€326,22 |
| 4 | Protegge +€20 dopo +€50 | -€3.744,04 | +€283,11 |
| 5 | Take profit fisso +€100 | -€3.833,20 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€3.959,55 | +€67,61 |
| 7 | Strategia attuale | -€4.027,16 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.027,16 | €0,00 |
| 9 | Take profit fisso +€200 | -€4.027,16 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.488,91 | -€461,75 |
| 11 | Take profit fisso +€75 | -€4.682,37 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€6.148,81 | -€2.121,65 |
| 13 | Take profit fisso +€25 | -€6.648,92 | -€2.621,76 |
| 14 | Take profit fisso +€50 | -€7.719,39 | -€3.692,23 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
