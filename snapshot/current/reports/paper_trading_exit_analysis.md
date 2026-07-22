# Analisi uscite paper trading a leva

Generato: 2026-07-22T13:08:47+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **732**
- Trade con percorso cronologico utilizzabile: **678**
- Trade che hanno raggiunto almeno +€50: **283**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.031,58 | +€1.417,53 |
| 2 | Protegge +€30 dopo +€50 | -€2.921,54 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€3.118,89 | +€330,22 |
| 4 | Take profit fisso +€100 | -€3.255,15 | +€193,95 |
| 5 | Pareggio dopo +€50 | -€3.381,50 | +€67,61 |
| 6 | Chiude 50% a +€50 | -€3.426,39 | +€22,71 |
| 7 | Strategia attuale | -€3.449,11 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.449,11 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.449,11 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€3.908,41 | -€459,31 |
| 11 | Take profit fisso +€75 | -€4.087,36 | -€638,25 |
| 12 | TP +€50 / SL -€50 | -€5.439,07 | -€1.989,96 |
| 13 | Take profit fisso +€25 | -€6.128,87 | -€2.679,76 |
| 14 | Take profit fisso +€50 | -€6.872,59 | -€3.423,49 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
