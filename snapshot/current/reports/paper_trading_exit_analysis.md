# Analisi uscite paper trading a leva

Generato: 2026-07-28T20:55:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3247**
- Trade con percorso cronologico utilizzabile: **3193**
- Trade che hanno raggiunto almeno +€50: **1331**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.644,92 | +€11.640,55 |
| 2 | Chiude 50% a +€50 | -€2.800,25 | +€2.195,38 |
| 3 | Protegge +€30 dopo +€50 | -€3.780,63 | +€1.215,00 |
| 4 | Protegge +€20 dopo +€50 | -€4.544,35 | +€451,28 |
| 5 | TP +€50 / SL -€50 | -€4.907,10 | +€88,54 |
| 6 | Strategia attuale | -€4.995,63 | €0,00 |
| 7 | Take profit fisso +€200 | -€4.995,63 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.999,95 | -€4,32 |
| 9 | Take profit fisso +€100 | -€5.202,67 | -€207,03 |
| 10 | Trailing 20% dopo +€50 | -€5.315,83 | -€320,20 |
| 11 | Pareggio dopo +€50 | -€6.175,66 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€9.474,18 | -€4.478,54 |
| 13 | Take profit fisso +€50 | -€16.409,52 | -€11.413,88 |
| 14 | Take profit fisso +€25 | -€17.104,74 | -€12.109,11 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
