# Analisi uscite paper trading a leva

Generato: 2026-07-28T21:55:25+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3268**
- Trade con percorso cronologico utilizzabile: **3214**
- Trade che hanno raggiunto almeno +€50: **1335**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.954,34 | +€11.766,86 |
| 2 | Chiude 50% a +€50 | -€3.548,23 | +€2.264,29 |
| 3 | Protegge +€30 dopo +€50 | -€4.539,71 | +€1.272,81 |
| 4 | Protegge +€20 dopo +€50 | -€5.343,43 | +€469,09 |
| 5 | TP +€50 / SL -€50 | -€5.459,86 | +€352,66 |
| 6 | Strategia attuale | -€5.812,52 | €0,00 |
| 7 | Take profit fisso +€200 | -€5.812,52 | €0,00 |
| 8 | Take profit fisso +€150 | -€5.816,84 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€5.923,75 | -€111,23 |
| 10 | Take profit fisso +€100 | -€6.019,55 | -€207,03 |
| 11 | Pareggio dopo +€50 | -€6.992,54 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€10.053,25 | -€4.240,73 |
| 13 | Take profit fisso +€50 | -€17.088,59 | -€11.276,07 |
| 14 | Take profit fisso +€25 | -€17.801,69 | -€11.989,17 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
