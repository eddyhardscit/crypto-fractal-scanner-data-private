# Analisi uscite paper trading a leva

Generato: 2026-07-20T18:23:37+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **404**
- Trade con percorso cronologico utilizzabile: **350**
- Trade che hanno raggiunto almeno +€50: **175**
- Di questi, chiusi poi in perdita: **45**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.190,21 | +€479,41 |
| 2 | Stop loss fisso -€50 | +€1.076,52 | +€365,73 |
| 3 | Protegge +€20 dopo +€50 | +€989,62 | +€278,82 |
| 4 | Chiude 50% a +€50 | +€797,33 | +€86,54 |
| 5 | Pareggio dopo +€50 | +€777,40 | +€66,61 |
| 6 | Take profit fisso +€100 | +€733,94 | +€23,14 |
| 7 | Strategia attuale | +€710,80 | €0,00 |
| 8 | Take profit fisso +€150 | +€710,80 | €0,00 |
| 9 | Take profit fisso +€200 | +€710,80 | €0,00 |
| 10 | Trailing 20% dopo +€50 | +€401,40 | -€309,40 |
| 11 | Take profit fisso +€75 | -€37,56 | -€748,36 |
| 12 | TP +€50 / SL -€50 | -€1.007,87 | -€1.718,67 |
| 13 | Take profit fisso +€50 | -€1.389,59 | -€2.100,39 |
| 14 | Take profit fisso +€25 | -€1.711,83 | -€2.422,62 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
