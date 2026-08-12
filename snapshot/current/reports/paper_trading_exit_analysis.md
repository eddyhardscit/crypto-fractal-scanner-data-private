# Analisi uscite paper trading a leva

Generato: 2026-08-12T13:43:29+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4454**
- Trade con percorso cronologico utilizzabile: **4400**
- Trade che hanno raggiunto almeno +€50: **1678**
- Di questi, chiusi poi in perdita: **343**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€5.358,90 | +€16.124,34 |
| 2 | TP +€50 / SL -€50 | -€14.740,18 | +€6.743,07 |
| 3 | Chiude 50% a +€50 | -€16.776,84 | +€4.706,40 |
| 4 | Protegge +€30 dopo +€50 | -€16.994,11 | +€4.489,14 |
| 5 | Protegge +€20 dopo +€50 | -€19.098,82 | +€2.384,43 |
| 6 | Strategia attuale | -€21.483,25 | €0,00 |
| 7 | Take profit fisso +€200 | -€21.483,25 | €0,00 |
| 8 | Take profit fisso +€150 | -€21.487,56 | -€4,32 |
| 9 | Take profit fisso +€100 | -€21.827,76 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€21.943,95 | -€460,70 |
| 11 | Pareggio dopo +€50 | -€22.986,26 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€25.201,75 | -€3.718,50 |
| 13 | Take profit fisso +€50 | -€30.671,81 | -€9.188,56 |
| 14 | Take profit fisso +€25 | -€33.710,07 | -€12.226,83 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
