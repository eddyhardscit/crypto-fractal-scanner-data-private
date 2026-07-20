# Analisi uscite paper trading a leva

Generato: 2026-07-20T13:23:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **378**
- Trade con percorso cronologico utilizzabile: **324**
- Trade che hanno raggiunto almeno +€50: **167**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.966,98 | +€449,20 |
| 2 | Stop loss fisso -€50 | +€1.819,18 | +€301,41 |
| 3 | Protegge +€20 dopo +€50 | +€1.776,39 | +€258,62 |
| 4 | Pareggio dopo +€50 | +€1.584,17 | +€66,40 |
| 5 | Take profit fisso +€100 | +€1.540,91 | +€23,14 |
| 6 | Strategia attuale | +€1.517,77 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.517,77 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.517,77 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.416,27 | -€101,50 |
| 10 | Trailing 20% dopo +€50 | +€1.146,60 | -€371,18 |
| 11 | Take profit fisso +€75 | +€694,21 | -€823,57 |
| 12 | TP +€50 / SL -€50 | -€295,45 | -€1.813,23 |
| 13 | Take profit fisso +€50 | -€612,85 | -€2.130,63 |
| 14 | Take profit fisso +€25 | -€1.080,93 | -€2.598,70 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
