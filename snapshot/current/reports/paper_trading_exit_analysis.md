# Analisi uscite paper trading a leva

Generato: 2026-07-27T10:09:37+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2413**
- Trade con percorso cronologico utilizzabile: **2359**
- Trade che hanno raggiunto almeno +€50: **1084**
- Di questi, chiusi poi in perdita: **200**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€12.333,28 | +€9.312,16 |
| 2 | Protegge +€30 dopo +€50 | +€4.434,85 | +€1.413,73 |
| 3 | Protegge +€20 dopo +€50 | +€3.681,67 | +€660,55 |
| 4 | Chiude 50% a +€50 | +€3.141,63 | +€120,51 |
| 5 | Trailing 20% dopo +€50 | +€3.139,35 | +€118,23 |
| 6 | Strategia attuale | +€3.021,12 | €0,00 |
| 7 | Take profit fisso +€200 | +€3.021,12 | €0,00 |
| 8 | Take profit fisso +€150 | +€3.016,80 | -€4,32 |
| 9 | Take profit fisso +€100 | +€2.936,93 | -€84,19 |
| 10 | Pareggio dopo +€50 | +€2.226,94 | -€794,18 |
| 11 | TP +€50 / SL -€50 | +€1.073,55 | -€1.947,57 |
| 12 | Take profit fisso +€75 | -€935,50 | -€3.956,62 |
| 13 | Take profit fisso +€50 | -€8.100,48 | -€11.121,60 |
| 14 | Take profit fisso +€25 | -€14.326,00 | -€17.347,12 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
