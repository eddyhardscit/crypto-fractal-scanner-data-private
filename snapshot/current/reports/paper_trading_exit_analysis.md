# Analisi uscite paper trading a leva

Generato: 2026-07-21T05:38:40+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **421**
- Trade con percorso cronologico utilizzabile: **367**
- Trade che hanno raggiunto almeno +€50: **179**
- Di questi, chiusi poi in perdita: **45**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€829,97 | +€506,54 |
| 2 | Stop loss fisso -€50 | +€727,00 | +€403,57 |
| 3 | Protegge +€20 dopo +€50 | +€619,39 | +€295,96 |
| 4 | Chiude 50% a +€50 | +€449,41 | +€125,98 |
| 5 | Pareggio dopo +€50 | +€390,04 | +€66,61 |
| 6 | Take profit fisso +€100 | +€346,57 | +€23,14 |
| 7 | Strategia attuale | +€323,43 | €0,00 |
| 8 | Take profit fisso +€150 | +€323,43 | €0,00 |
| 9 | Take profit fisso +€200 | +€323,43 | €0,00 |
| 10 | Trailing 20% dopo +€50 | +€31,36 | -€292,07 |
| 11 | Take profit fisso +€75 | -€417,32 | -€740,75 |
| 12 | TP +€50 / SL -€50 | -€1.322,53 | -€1.645,96 |
| 13 | Take profit fisso +€50 | -€1.742,10 | -€2.065,53 |
| 14 | Take profit fisso +€25 | -€2.028,76 | -€2.352,19 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
