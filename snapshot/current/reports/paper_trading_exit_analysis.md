# Analisi uscite paper trading a leva

Generato: 2026-07-20T03:08:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **312**
- Trade con percorso cronologico utilizzabile: **258**
- Trade che hanno raggiunto almeno +€50: **135**
- Di questi, chiusi poi in perdita: **30**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.028,09 | +€405,22 |
| 2 | Protegge +€20 dopo +€50 | +€1.875,82 | +€252,95 |
| 3 | Stop loss fisso -€50 | +€1.846,86 | +€223,99 |
| 4 | Take profit fisso +€100 | +€1.701,28 | +€78,41 |
| 5 | Pareggio dopo +€50 | +€1.678,94 | +€56,07 |
| 6 | Strategia attuale | +€1.622,87 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.622,87 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.622,87 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.400,60 | -€222,27 |
| 10 | Trailing 20% dopo +€50 | +€1.150,27 | -€472,60 |
| 11 | Take profit fisso +€75 | +€868,81 | -€754,05 |
| 12 | TP +€50 / SL -€50 | -€38,59 | -€1.661,46 |
| 13 | Take profit fisso +€50 | -€278,58 | -€1.901,45 |
| 14 | Take profit fisso +€25 | -€733,56 | -€2.356,42 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
