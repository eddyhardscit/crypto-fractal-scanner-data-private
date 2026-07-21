# Analisi uscite paper trading a leva

Generato: 2026-07-21T01:38:38+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **410**
- Trade con percorso cronologico utilizzabile: **356**
- Trade che hanno raggiunto almeno +€50: **177**
- Di questi, chiusi poi in perdita: **45**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.220,42 | +€479,41 |
| 2 | Stop loss fisso -€50 | +€1.106,74 | +€365,73 |
| 3 | Protegge +€20 dopo +€50 | +€1.019,84 | +€278,82 |
| 4 | Chiude 50% a +€50 | +€852,13 | +€111,11 |
| 5 | Pareggio dopo +€50 | +€807,62 | +€66,61 |
| 6 | Take profit fisso +€100 | +€764,16 | +€23,14 |
| 7 | Strategia attuale | +€741,02 | €0,00 |
| 8 | Take profit fisso +€150 | +€741,02 | €0,00 |
| 9 | Take profit fisso +€200 | +€741,02 | €0,00 |
| 10 | Trailing 20% dopo +€50 | +€426,64 | -€314,38 |
| 11 | Take profit fisso +€75 | -€7,34 | -€748,36 |
| 12 | TP +€50 / SL -€50 | -€972,53 | -€1.713,55 |
| 13 | Take profit fisso +€50 | -€1.354,25 | -€2.095,27 |
| 14 | Take profit fisso +€25 | -€1.590,92 | -€2.331,93 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
