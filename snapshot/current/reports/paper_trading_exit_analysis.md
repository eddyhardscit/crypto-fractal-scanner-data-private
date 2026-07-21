# Analisi uscite paper trading a leva

Generato: 2026-07-21T19:53:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **562**
- Trade con percorso cronologico utilizzabile: **508**
- Trade che hanno raggiunto almeno +€50: **249**
- Di questi, chiusi poi in perdita: **60**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€996,10 | +€888,21 |
| 2 | Protegge +€30 dopo +€50 | +€637,69 | +€529,80 |
| 3 | Protegge +€20 dopo +€50 | +€397,11 | +€289,21 |
| 4 | Chiude 50% a +€50 | +€361,96 | +€254,07 |
| 5 | Take profit fisso +€100 | +€294,26 | +€186,37 |
| 6 | Pareggio dopo +€50 | +€174,50 | +€66,61 |
| 7 | Strategia attuale | +€107,89 | €0,00 |
| 8 | Take profit fisso +€150 | +€107,89 | €0,00 |
| 9 | Take profit fisso +€200 | +€107,89 | €0,00 |
| 10 | Take profit fisso +€75 | -€355,73 | -€463,62 |
| 11 | Trailing 20% dopo +€50 | -€386,46 | -€494,35 |
| 12 | TP +€50 / SL -€50 | -€1.753,50 | -€1.861,40 |
| 13 | Take profit fisso +€50 | -€2.657,70 | -€2.765,59 |
| 14 | Take profit fisso +€25 | -€3.382,96 | -€3.490,85 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
