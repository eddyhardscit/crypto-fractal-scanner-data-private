# Analisi uscite paper trading a leva

Generato: 2026-08-12T23:28:12+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4663**
- Trade con percorso cronologico utilizzabile: **4609**
- Trade che hanno raggiunto almeno +€50: **1773**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.885,39 | +€16.479,93 |
| 2 | TP +€50 / SL -€50 | -€14.627,14 | +€4.738,19 |
| 3 | Protegge +€30 dopo +€50 | -€14.809,66 | +€4.555,66 |
| 4 | Chiude 50% a +€50 | -€15.486,60 | +€3.878,73 |
| 5 | Protegge +€20 dopo +€50 | -€16.980,90 | +€2.384,43 |
| 6 | Strategia attuale | -€19.365,33 | €0,00 |
| 7 | Take profit fisso +€200 | -€19.365,33 | €0,00 |
| 8 | Take profit fisso +€150 | -€19.369,64 | -€4,32 |
| 9 | Take profit fisso +€100 | -€19.873,01 | -€507,68 |
| 10 | Trailing 20% dopo +€50 | -€20.122,16 | -€756,83 |
| 11 | Pareggio dopo +€50 | -€20.868,33 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€24.086,87 | -€4.721,54 |
| 13 | Take profit fisso +€50 | -€30.914,36 | -€11.549,03 |
| 14 | Take profit fisso +€25 | -€35.397,30 | -€16.031,98 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
