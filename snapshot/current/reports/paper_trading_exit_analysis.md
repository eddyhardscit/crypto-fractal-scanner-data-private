# Analisi uscite paper trading a leva

Generato: 2026-07-31T15:28:14+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3474**
- Trade con percorso cronologico utilizzabile: **3420**
- Trade che hanno raggiunto almeno +€50: **1401**
- Di questi, chiusi poi in perdita: **286**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.406,37 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€3.497,26 | +€3.090,85 |
| 3 | Protegge +€30 dopo +€50 | -€4.963,97 | +€1.624,15 |
| 4 | TP +€50 / SL -€50 | -€5.465,05 | +€1.123,07 |
| 5 | Protegge +€20 dopo +€50 | -€5.850,26 | +€737,86 |
| 6 | Trailing 20% dopo +€50 | -€6.533,62 | +€54,50 |
| 7 | Strategia attuale | -€6.588,12 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.588,12 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.592,43 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.803,35 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.706,77 | -€1.118,65 |
| 12 | Take profit fisso +€75 | -€10.120,90 | -€3.532,78 |
| 13 | Take profit fisso +€50 | -€17.320,48 | -€10.732,36 |
| 14 | Take profit fisso +€25 | -€17.512,62 | -€10.924,50 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
