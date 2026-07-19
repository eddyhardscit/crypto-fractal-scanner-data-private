# Analisi uscite paper trading a leva

Generato: 2026-07-19T08:53:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **241**
- Trade con percorso cronologico utilizzabile: **187**
- Trade che hanno raggiunto almeno +€50: **104**
- Di questi, chiusi poi in perdita: **19**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.062,20 | +€265,54 |
| 2 | Protegge +€20 dopo +€50 | +€1.959,93 | +€163,27 |
| 3 | Stop loss fisso -€50 | +€1.920,79 | +€124,14 |
| 4 | Pareggio dopo +€50 | +€1.852,04 | +€55,38 |
| 5 | Strategia attuale | +€1.796,66 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.796,66 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.796,66 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.766,57 | -€30,08 |
| 9 | Chiude 50% a +€50 | +€1.460,45 | -€336,20 |
| 10 | Trailing 20% dopo +€50 | +€1.314,78 | -€481,87 |
| 11 | Take profit fisso +€75 | +€1.100,31 | -€696,35 |
| 12 | TP +€50 / SL -€50 | +€358,03 | -€1.438,63 |
| 13 | Take profit fisso +€50 | +€217,90 | -€1.578,76 |
| 14 | Take profit fisso +€25 | -€448,12 | -€2.244,77 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
