# Analisi uscite paper trading a leva

Generato: 2026-07-21T14:53:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **489**
- Trade con percorso cronologico utilizzabile: **435**
- Trade che hanno raggiunto almeno +€50: **203**
- Di questi, chiusi poi in perdita: **54**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€96,45 | +€847,46 |
| 2 | Protegge +€30 dopo +€50 | -€437,37 | +€506,54 |
| 3 | Protegge +€20 dopo +€50 | -€647,96 | +€295,96 |
| 4 | Chiude 50% a +€50 | -€732,57 | +€211,34 |
| 5 | Take profit fisso +€100 | -€757,14 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€877,31 | +€66,61 |
| 7 | Strategia attuale | -€943,92 | €0,00 |
| 8 | Take profit fisso +€150 | -€943,92 | €0,00 |
| 9 | Take profit fisso +€200 | -€943,92 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€1.321,24 | -€377,32 |
| 11 | Take profit fisso +€75 | -€1.771,14 | -€827,22 |
| 12 | TP +€50 / SL -€50 | -€2.555,02 | -€1.611,11 |
| 13 | Take profit fisso +€50 | -€3.418,48 | -€2.474,56 |
| 14 | Take profit fisso +€25 | -€3.425,44 | -€2.481,53 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
