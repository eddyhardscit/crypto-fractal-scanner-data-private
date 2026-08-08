# Analisi uscite paper trading a leva

Generato: 2026-08-08T19:41:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3628**
- Trade con percorso cronologico utilizzabile: **3574**
- Trade che hanno raggiunto almeno +€50: **1408**
- Di questi, chiusi poi in perdita: **290**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.234,31 | +€11.996,14 |
| 2 | Chiude 50% a +€50 | -€3.519,83 | +€3.242,00 |
| 3 | Protegge +€30 dopo +€50 | -€5.022,13 | +€1.739,70 |
| 4 | TP +€50 / SL -€50 | -€5.435,34 | +€1.326,49 |
| 5 | Protegge +€20 dopo +€50 | -€5.948,42 | +€813,41 |
| 6 | Trailing 20% dopo +€50 | -€6.653,04 | +€108,79 |
| 7 | Strategia attuale | -€6.761,83 | €0,00 |
| 8 | Take profit fisso +€200 | -€6.761,83 | €0,00 |
| 9 | Take profit fisso +€150 | -€6.766,14 | -€4,32 |
| 10 | Take profit fisso +€100 | -€6.977,07 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€7.884,93 | -€1.123,10 |
| 12 | Take profit fisso +€75 | -€10.171,96 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€17.193,68 | -€10.431,85 |
| 14 | Take profit fisso +€50 | -€17.292,43 | -€10.530,60 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
