# Analisi uscite paper trading a leva

Generato: 2026-08-12T11:30:15+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4427**
- Trade con percorso cronologico utilizzabile: **4373**
- Trade che hanno raggiunto almeno +€50: **1676**
- Di questi, chiusi poi in perdita: **343**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.388,10 | +€16.064,85 |
| 2 | TP +€50 / SL -€50 | -€13.769,37 | +€6.683,58 |
| 3 | Chiude 50% a +€50 | -€15.769,57 | +€4.683,38 |
| 4 | Protegge +€30 dopo +€50 | -€15.963,81 | +€4.489,14 |
| 5 | Protegge +€20 dopo +€50 | -€18.068,52 | +€2.384,43 |
| 6 | Strategia attuale | -€20.452,95 | €0,00 |
| 7 | Take profit fisso +€200 | -€20.452,95 | €0,00 |
| 8 | Take profit fisso +€150 | -€20.457,27 | -€4,32 |
| 9 | Take profit fisso +€100 | -€20.797,47 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€20.913,66 | -€460,70 |
| 11 | Pareggio dopo +€50 | -€21.955,96 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€24.171,45 | -€3.718,50 |
| 13 | Take profit fisso +€50 | -€29.641,51 | -€9.188,56 |
| 14 | Take profit fisso +€25 | -€32.675,82 | -€12.222,87 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
