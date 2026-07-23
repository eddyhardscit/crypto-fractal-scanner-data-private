# Analisi uscite paper trading a leva

Generato: 2026-07-23T20:38:54+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **962**
- Trade con percorso cronologico utilizzabile: **908**
- Trade che hanno raggiunto almeno +€50: **395**
- Di questi, chiusi poi in perdita: **88**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€991,08 | +€2.028,40 |
| 2 | Take profit fisso +€100 | -€2.906,09 | +€113,39 |
| 3 | Chiude 50% a +€50 | -€2.915,30 | +€104,18 |
| 4 | Strategia attuale | -€3.019,48 | €0,00 |
| 5 | Take profit fisso +€150 | -€3.019,48 | €0,00 |
| 6 | Take profit fisso +€200 | -€3.019,48 | €0,00 |
| 7 | Protegge +€20 dopo +€50 | -€3.362,55 | -€343,07 |
| 8 | Protegge +€30 dopo +€50 | -€3.399,66 | -€380,18 |
| 9 | Take profit fisso +€75 | -€3.888,93 | -€869,45 |
| 10 | Pareggio dopo +€50 | -€3.937,19 | -€917,70 |
| 11 | Trailing 20% dopo +€50 | -€4.619,68 | -€1.600,20 |
| 12 | TP +€50 / SL -€50 | -€5.769,79 | -€2.750,31 |
| 13 | Take profit fisso +€25 | -€7.346,70 | -€4.327,21 |
| 14 | Take profit fisso +€50 | -€7.814,18 | -€4.794,70 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
