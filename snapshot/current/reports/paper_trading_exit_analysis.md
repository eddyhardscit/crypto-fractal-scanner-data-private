# Analisi uscite paper trading a leva

Generato: 2026-07-21T15:53:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **521**
- Trade con percorso cronologico utilizzabile: **467**
- Trade che hanno raggiunto almeno +€50: **217**
- Di questi, chiusi poi in perdita: **60**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€708,09 | +€866,33 |
| 2 | Protegge +€30 dopo +€50 | -€1.044,62 | +€529,80 |
| 3 | Chiude 50% a +€50 | -€1.134,31 | +€440,11 |
| 4 | Protegge +€20 dopo +€50 | -€1.285,21 | +€289,21 |
| 5 | Take profit fisso +€100 | -€1.387,65 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€1.507,81 | +€66,61 |
| 7 | Strategia attuale | -€1.574,42 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.574,42 | €0,00 |
| 9 | Take profit fisso +€200 | -€1.574,42 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€1.808,17 | -€233,75 |
| 11 | Take profit fisso +€75 | -€2.187,84 | -€613,42 |
| 12 | TP +€50 / SL -€50 | -€3.036,25 | -€1.461,83 |
| 13 | Take profit fisso +€50 | -€3.918,57 | -€2.344,15 |
| 14 | Take profit fisso +€25 | -€3.918,93 | -€2.344,51 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
