# Analisi uscite paper trading a leva

Generato: 2026-08-11T17:16:27+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3954**
- Trade con percorso cronologico utilizzabile: **3900**
- Trade che hanno raggiunto almeno +€50: **1524**
- Di questi, chiusi poi in perdita: **297**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€4.737,38 | +€13.898,09 |
| 2 | Chiude 50% a +€50 | -€6.722,51 | +€2.438,21 |
| 3 | Protegge +€30 dopo +€50 | -€6.873,05 | +€2.287,66 |
| 4 | Protegge +€20 dopo +€50 | -€7.940,78 | +€1.219,93 |
| 5 | TP +€50 / SL -€50 | -€8.222,35 | +€938,37 |
| 6 | Strategia attuale | -€9.160,71 | €0,00 |
| 7 | Take profit fisso +€200 | -€9.160,71 | €0,00 |
| 8 | Take profit fisso +€150 | -€9.165,03 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€9.303,04 | -€142,32 |
| 10 | Take profit fisso +€100 | -€9.505,23 | -€344,52 |
| 11 | Pareggio dopo +€50 | -€10.070,05 | -€909,34 |
| 12 | Take profit fisso +€75 | -€13.864,75 | -€4.704,03 |
| 13 | Take profit fisso +€50 | -€21.981,39 | -€12.820,67 |
| 14 | Take profit fisso +€25 | -€23.926,97 | -€14.766,26 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
