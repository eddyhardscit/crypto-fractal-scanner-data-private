# Analisi uscite paper trading a leva

Generato: 2026-07-21T13:38:43+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **470**
- Trade con percorso cronologico utilizzabile: **416**
- Trade che hanno raggiunto almeno +€50: **199**
- Di questi, chiusi poi in perdita: **54**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€229,76 | +€779,11 |
| 2 | Protegge +€30 dopo +€50 | -€42,81 | +€506,54 |
| 3 | Protegge +€20 dopo +€50 | -€253,39 | +€295,96 |
| 4 | Chiude 50% a +€50 | -€272,77 | +€276,58 |
| 5 | Take profit fisso +€100 | -€362,57 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€482,74 | +€66,61 |
| 7 | Strategia attuale | -€549,35 | €0,00 |
| 8 | Take profit fisso +€150 | -€549,35 | €0,00 |
| 9 | Take profit fisso +€200 | -€549,35 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€844,05 | -€294,70 |
| 11 | Take profit fisso +€75 | -€1.332,30 | -€782,95 |
| 12 | TP +€50 / SL -€50 | -€2.098,34 | -€1.548,99 |
| 13 | Take profit fisso +€25 | -€2.800,40 | -€2.251,05 |
| 14 | Take profit fisso +€50 | -€2.893,44 | -€2.344,09 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
