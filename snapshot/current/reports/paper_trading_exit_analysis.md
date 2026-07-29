# Analisi uscite paper trading a leva

Generato: 2026-07-29T03:55:09+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3306**
- Trade con percorso cronologico utilizzabile: **3252**
- Trade che hanno raggiunto almeno +€50: **1348**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.388,64 | +€11.849,86 |
| 2 | Chiude 50% a +€50 | -€3.328,28 | +€2.132,95 |
| 3 | Protegge +€30 dopo +€50 | -€4.243,73 | +€1.217,50 |
| 4 | Protegge +€20 dopo +€50 | -€4.992,13 | +€469,09 |
| 5 | TP +€50 / SL -€50 | -€5.436,04 | +€25,19 |
| 6 | Strategia attuale | -€5.461,22 | €0,00 |
| 7 | Take profit fisso +€200 | -€5.461,22 | €0,00 |
| 8 | Take profit fisso +€150 | -€5.465,54 | -€4,32 |
| 9 | Take profit fisso +€100 | -€5.676,46 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€6.152,98 | -€691,76 |
| 11 | Pareggio dopo +€50 | -€6.641,25 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€9.862,43 | -€4.401,20 |
| 13 | Take profit fisso +€50 | -€17.147,77 | -€11.686,55 |
| 14 | Take profit fisso +€25 | -€17.968,68 | -€12.507,46 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
