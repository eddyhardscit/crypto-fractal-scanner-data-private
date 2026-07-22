# Analisi uscite paper trading a leva

Generato: 2026-07-22T04:08:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **630**
- Trade con percorso cronologico utilizzabile: **576**
- Trade che hanno raggiunto almeno +€50: **263**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€63,37 | +€1.014,82 |
| 2 | Protegge +€30 dopo +€50 | -€487,39 | +€590,80 |
| 3 | Chiude 50% a +€50 | -€728,18 | +€350,02 |
| 4 | Protegge +€20 dopo +€50 | -€747,97 | +€330,22 |
| 5 | Take profit fisso +€100 | -€891,82 | +€186,37 |
| 6 | Pareggio dopo +€50 | -€1.010,58 | +€67,61 |
| 7 | Strategia attuale | -€1.078,19 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.078,19 | €0,00 |
| 9 | Take profit fisso +€200 | -€1.078,19 | €0,00 |
| 10 | Take profit fisso +€75 | -€1.476,63 | -€398,44 |
| 11 | Trailing 20% dopo +€50 | -€1.484,01 | -€405,82 |
| 12 | TP +€50 / SL -€50 | -€2.816,26 | -€1.738,07 |
| 13 | Take profit fisso +€25 | -€3.764,05 | -€2.685,86 |
| 14 | Take profit fisso +€50 | -€3.847,07 | -€2.768,88 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
