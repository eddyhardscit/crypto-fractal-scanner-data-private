# Analisi uscite paper trading a leva

Generato: 2026-07-20T07:08:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **332**
- Trade con percorso cronologico utilizzabile: **278**
- Trade che hanno raggiunto almeno +€50: **141**
- Di questi, chiusi poi in perdita: **33**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.515,52 | +€287,52 |
| 2 | Stop loss fisso -€50 | +€1.499,95 | +€271,95 |
| 3 | Protegge +€20 dopo +€50 | +€1.394,93 | +€166,93 |
| 4 | Take profit fisso +€100 | +€1.300,39 | +€72,39 |
| 5 | Pareggio dopo +€50 | +€1.284,07 | +€56,07 |
| 6 | Strategia attuale | +€1.228,00 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.228,00 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.228,00 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.052,61 | -€175,39 |
| 10 | Trailing 20% dopo +€50 | +€621,82 | -€606,17 |
| 11 | Take profit fisso +€75 | +€442,93 | -€785,07 |
| 12 | TP +€50 / SL -€50 | -€463,21 | -€1.691,20 |
| 13 | Take profit fisso +€50 | -€751,15 | -€1.979,15 |
| 14 | Take profit fisso +€25 | -€1.105,54 | -€2.333,54 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
