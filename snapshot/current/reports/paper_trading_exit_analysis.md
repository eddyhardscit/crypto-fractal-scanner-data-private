# Analisi uscite paper trading a leva

Generato: 2026-07-24T13:54:46+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1115**
- Trade con percorso cronologico utilizzabile: **1061**
- Trade che hanno raggiunto almeno +€50: **486**
- Di questi, chiusi poi in perdita: **114**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€804,60 | +€2.362,04 |
| 2 | Chiude 50% a +€50 | -€2.089,04 | +€1.077,60 |
| 3 | Take profit fisso +€100 | -€2.809,51 | +€357,12 |
| 4 | Protegge +€30 dopo +€50 | -€3.156,25 | +€10,38 |
| 5 | Strategia attuale | -€3.166,63 | €0,00 |
| 6 | Take profit fisso +€150 | -€3.166,63 | €0,00 |
| 7 | Take profit fisso +€200 | -€3.166,63 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€3.332,22 | -€165,59 |
| 9 | Take profit fisso +€75 | -€3.752,43 | -€585,80 |
| 10 | Pareggio dopo +€50 | -€4.072,02 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€4.166,73 | -€1.000,10 |
| 12 | TP +€50 / SL -€50 | -€5.272,43 | -€2.105,80 |
| 13 | Take profit fisso +€25 | -€7.598,78 | -€4.432,15 |
| 14 | Take profit fisso +€50 | -€7.650,46 | -€4.483,83 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
