# Analisi uscite paper trading a leva

Generato: 2026-07-27T22:09:41+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2637**
- Trade con percorso cronologico utilizzabile: **2583**
- Trade che hanno raggiunto almeno +€50: **1144**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.849,40 | +€9.643,85 |
| 2 | Protegge +€30 dopo +€50 | +€1.082,19 | +€876,64 |
| 3 | Chiude 50% a +€50 | +€849,32 | +€643,77 |
| 4 | Strategia attuale | +€205,55 | €0,00 |
| 5 | Take profit fisso +€200 | +€205,55 | €0,00 |
| 6 | Take profit fisso +€100 | +€203,32 | -€2,23 |
| 7 | Take profit fisso +€150 | +€201,24 | -€4,32 |
| 8 | Protegge +€20 dopo +€50 | +€164,26 | -€41,29 |
| 9 | Trailing 20% dopo +€50 | +€17,14 | -€188,41 |
| 10 | Pareggio dopo +€50 | -€588,62 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€1.596,13 | -€1.801,68 |
| 12 | Take profit fisso +€75 | -€3.501,20 | -€3.706,76 |
| 13 | Take profit fisso +€50 | -€11.101,85 | -€11.307,40 |
| 14 | Take profit fisso +€25 | -€14.383,12 | -€14.588,67 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
