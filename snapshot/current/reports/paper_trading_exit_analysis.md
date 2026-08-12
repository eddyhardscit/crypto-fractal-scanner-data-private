# Analisi uscite paper trading a leva

Generato: 2026-08-12T12:29:08+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4446**
- Trade con percorso cronologico utilizzabile: **4392**
- Trade che hanno raggiunto almeno +€50: **1676**
- Di questi, chiusi poi in perdita: **343**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€5.291,81 | +€16.118,46 |
| 2 | TP +€50 / SL -€50 | -€14.673,08 | +€6.737,19 |
| 3 | Chiude 50% a +€50 | -€16.726,89 | +€4.683,38 |
| 4 | Protegge +€30 dopo +€50 | -€16.921,13 | +€4.489,14 |
| 5 | Protegge +€20 dopo +€50 | -€19.025,84 | +€2.384,43 |
| 6 | Strategia attuale | -€21.410,27 | €0,00 |
| 7 | Take profit fisso +€200 | -€21.410,27 | €0,00 |
| 8 | Take profit fisso +€150 | -€21.414,59 | -€4,32 |
| 9 | Take profit fisso +€100 | -€21.754,78 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€21.870,97 | -€460,70 |
| 11 | Pareggio dopo +€50 | -€22.913,28 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€25.128,77 | -€3.718,50 |
| 13 | Take profit fisso +€50 | -€30.598,83 | -€9.188,56 |
| 14 | Take profit fisso +€25 | -€33.633,14 | -€12.222,87 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
