# Analisi uscite paper trading a leva

Generato: 2026-07-28T08:39:55+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2902**
- Trade con percorso cronologico utilizzabile: **2848**
- Trade che hanno raggiunto almeno +€50: **1251**
- Di questi, chiusi poi in perdita: **258**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€10.221,03 | +€10.919,78 |
| 2 | Chiude 50% a +€50 | +€1.086,66 | +€1.785,41 |
| 3 | Protegge +€30 dopo +€50 | +€527,62 | +€1.226,37 |
| 4 | Protegge +€20 dopo +€50 | -€333,57 | +€365,18 |
| 5 | Strategia attuale | -€698,75 | €0,00 |
| 6 | Take profit fisso +€200 | -€698,75 | €0,00 |
| 7 | Take profit fisso +€150 | -€703,07 | -€4,32 |
| 8 | Take profit fisso +€100 | -€813,60 | -€114,85 |
| 9 | Trailing 20% dopo +€50 | -€1.210,18 | -€511,43 |
| 10 | TP +€50 / SL -€50 | -€1.383,68 | -€684,93 |
| 11 | Pareggio dopo +€50 | -€1.642,36 | -€943,61 |
| 12 | Take profit fisso +€75 | -€4.941,85 | -€4.243,10 |
| 13 | Take profit fisso +€50 | -€12.165,33 | -€11.466,58 |
| 14 | Take profit fisso +€25 | -€13.307,30 | -€12.608,55 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
