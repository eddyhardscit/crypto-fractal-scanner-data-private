# Analisi uscite paper trading a leva

Generato: 2026-07-27T02:09:28+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2082**
- Trade con percorso cronologico utilizzabile: **2028**
- Trade che hanno raggiunto almeno +€50: **927**
- Di questi, chiusi poi in perdita: **193**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.046,92 | +€8.925,71 |
| 2 | Chiude 50% a +€50 | -€419,93 | +€1.458,86 |
| 3 | Protegge +€30 dopo +€50 | -€1.077,12 | +€801,67 |
| 4 | TP +€50 / SL -€50 | -€1.402,00 | +€476,79 |
| 5 | Protegge +€20 dopo +€50 | -€1.509,88 | +€368,91 |
| 6 | Strategia attuale | -€1.878,78 | €0,00 |
| 7 | Take profit fisso +€200 | -€1.878,78 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.879,52 | -€0,74 |
| 9 | Take profit fisso +€100 | -€1.938,44 | -€59,65 |
| 10 | Trailing 20% dopo +€50 | -€2.057,64 | -€178,85 |
| 11 | Pareggio dopo +€50 | -€2.721,65 | -€842,87 |
| 12 | Take profit fisso +€75 | -€4.965,12 | -€3.086,34 |
| 13 | Take profit fisso +€50 | -€10.189,58 | -€8.310,79 |
| 14 | Take profit fisso +€25 | -€14.289,63 | -€12.410,85 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
