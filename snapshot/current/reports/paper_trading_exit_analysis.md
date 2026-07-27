# Analisi uscite paper trading a leva

Generato: 2026-07-27T07:09:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2260**
- Trade con percorso cronologico utilizzabile: **2206**
- Trade che hanno raggiunto almeno +€50: **1063**
- Di questi, chiusi poi in perdita: **198**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€16.034,22 | +€9.037,67 |
| 2 | Protegge +€30 dopo +€50 | +€8.362,99 | +€1.366,44 |
| 3 | Protegge +€20 dopo +€50 | +€7.650,68 | +€654,13 |
| 4 | Strategia attuale | +€6.996,56 | €0,00 |
| 5 | Take profit fisso +€200 | +€6.996,56 | €0,00 |
| 6 | Take profit fisso +€150 | +€6.992,24 | -€4,32 |
| 7 | Chiude 50% a +€50 | +€6.928,47 | -€68,09 |
| 8 | Take profit fisso +€100 | +€6.912,36 | -€84,19 |
| 9 | Trailing 20% dopo +€50 | +€6.782,90 | -€213,66 |
| 10 | Pareggio dopo +€50 | +€6.202,38 | -€794,18 |
| 11 | TP +€50 / SL -€50 | +€4.524,70 | -€2.471,85 |
| 12 | Take profit fisso +€75 | +€2.838,87 | -€4.157,69 |
| 13 | Take profit fisso +€50 | -€4.374,83 | -€11.371,39 |
| 14 | Take profit fisso +€25 | -€11.771,91 | -€18.768,47 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
