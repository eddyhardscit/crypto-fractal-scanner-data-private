# Analisi uscite paper trading a leva

Generato: 2026-07-28T14:40:27+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2991**
- Trade con percorso cronologico utilizzabile: **2937**
- Trade che hanno raggiunto almeno +€50: **1276**
- Di questi, chiusi poi in perdita: **270**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.822,21 | +€11.099,63 |
| 2 | Chiude 50% a +€50 | +€581,64 | +€1.859,06 |
| 3 | Protegge +€30 dopo +€50 | -€130,44 | +€1.146,98 |
| 4 | Protegge +€20 dopo +€50 | -€705,23 | +€572,18 |
| 5 | Strategia attuale | -€1.277,42 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.277,42 | €0,00 |
| 7 | Take profit fisso +€150 | -€1.281,73 | -€4,32 |
| 8 | Take profit fisso +€100 | -€1.484,45 | -€207,03 |
| 9 | TP +€50 / SL -€50 | -€1.846,88 | -€569,46 |
| 10 | Trailing 20% dopo +€50 | -€1.899,29 | -€621,88 |
| 11 | Pareggio dopo +€50 | -€2.194,02 | -€916,60 |
| 12 | Take profit fisso +€75 | -€5.809,58 | -€4.532,17 |
| 13 | Take profit fisso +€50 | -€12.808,38 | -€11.530,96 |
| 14 | Take profit fisso +€25 | -€14.091,75 | -€12.814,34 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
