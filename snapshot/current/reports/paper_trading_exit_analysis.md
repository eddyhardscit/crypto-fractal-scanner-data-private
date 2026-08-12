# Analisi uscite paper trading a leva

Generato: 2026-08-12T21:47:15+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4628**
- Trade con percorso cronologico utilizzabile: **4574**
- Trade che hanno raggiunto almeno +€50: **1746**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€5.231,16 | +€16.464,62 |
| 2 | TP +€50 / SL -€50 | -€15.789,86 | +€5.905,92 |
| 3 | Protegge +€30 dopo +€50 | -€17.140,12 | +€4.555,66 |
| 4 | Chiude 50% a +€50 | -€17.225,53 | +€4.470,25 |
| 5 | Protegge +€20 dopo +€50 | -€19.311,35 | +€2.384,43 |
| 6 | Strategia attuale | -€21.695,78 | €0,00 |
| 7 | Take profit fisso +€200 | -€21.695,78 | €0,00 |
| 8 | Take profit fisso +€150 | -€21.700,10 | -€4,32 |
| 9 | Take profit fisso +€100 | -€22.059,04 | -€363,26 |
| 10 | Trailing 20% dopo +€50 | -€22.452,61 | -€756,83 |
| 11 | Pareggio dopo +€50 | -€23.198,79 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€25.878,29 | -€4.182,51 |
| 13 | Take profit fisso +€50 | -€32.061,77 | -€10.365,99 |
| 14 | Take profit fisso +€25 | -€35.869,72 | -€14.173,94 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
