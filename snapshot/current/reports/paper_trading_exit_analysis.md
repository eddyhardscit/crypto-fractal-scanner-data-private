# Analisi uscite paper trading a leva

Generato: 2026-07-25T02:09:12+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1252**
- Trade con percorso cronologico utilizzabile: **1198**
- Trade che hanno raggiunto almeno +€50: **571**
- Di questi, chiusi poi in perdita: **133**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€1.097,08 | +€2.782,68 |
| 2 | Chiude 50% a +€50 | -€185,21 | +€1.500,38 |
| 3 | Take profit fisso +€100 | -€1.397,61 | +€287,99 |
| 4 | Strategia attuale | -€1.685,60 | €0,00 |
| 5 | Take profit fisso +€150 | -€1.685,60 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.685,60 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€1.790,56 | -€104,96 |
| 8 | Protegge +€20 dopo +€50 | -€2.117,49 | -€431,89 |
| 9 | Take profit fisso +€75 | -€2.732,73 | -€1.047,13 |
| 10 | Pareggio dopo +€50 | -€2.859,14 | -€1.173,54 |
| 11 | Trailing 20% dopo +€50 | -€3.017,68 | -€1.332,08 |
| 12 | TP +€50 / SL -€50 | -€3.938,76 | -€2.253,16 |
| 13 | Take profit fisso +€50 | -€6.737,43 | -€5.051,84 |
| 14 | Take profit fisso +€25 | -€7.090,85 | -€5.405,25 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
