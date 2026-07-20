# Analisi uscite paper trading a leva

Generato: 2026-07-20T19:23:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **407**
- Trade con percorso cronologico utilizzabile: **353**
- Trade che hanno raggiunto almeno +€50: **176**
- Di questi, chiusi poi in perdita: **45**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.224,00 | +€479,41 |
| 2 | Stop loss fisso -€50 | +€1.110,32 | +€365,73 |
| 3 | Protegge +€20 dopo +€50 | +€1.023,42 | +€278,82 |
| 4 | Chiude 50% a +€50 | +€833,69 | +€89,10 |
| 5 | Pareggio dopo +€50 | +€811,20 | +€66,61 |
| 6 | Take profit fisso +€100 | +€767,74 | +€23,14 |
| 7 | Strategia attuale | +€744,59 | €0,00 |
| 8 | Take profit fisso +€150 | +€744,59 | €0,00 |
| 9 | Take profit fisso +€200 | +€744,59 | €0,00 |
| 10 | Trailing 20% dopo +€50 | +€430,22 | -€314,38 |
| 11 | Take profit fisso +€75 | -€3,77 | -€748,36 |
| 12 | TP +€50 / SL -€50 | -€968,95 | -€1.713,55 |
| 13 | Take profit fisso +€50 | -€1.350,67 | -€2.095,27 |
| 14 | Take profit fisso +€25 | -€1.636,83 | -€2.381,42 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
