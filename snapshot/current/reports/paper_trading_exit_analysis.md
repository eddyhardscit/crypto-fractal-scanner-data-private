# Analisi uscite paper trading a leva

Generato: 2026-07-23T18:38:53+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **955**
- Trade con percorso cronologico utilizzabile: **901**
- Trade che hanno raggiunto almeno +€50: **393**
- Di questi, chiusi poi in perdita: **87**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€928,88 | +€2.018,37 |
| 2 | Take profit fisso +€100 | -€2.833,86 | +€113,39 |
| 3 | Chiude 50% a +€50 | -€2.877,68 | +€69,57 |
| 4 | Strategia attuale | -€2.947,25 | €0,00 |
| 5 | Take profit fisso +€150 | -€2.947,25 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.947,25 | €0,00 |
| 7 | Protegge +€20 dopo +€50 | -€3.312,21 | -€364,96 |
| 8 | Protegge +€30 dopo +€50 | -€3.359,32 | -€412,07 |
| 9 | Pareggio dopo +€50 | -€3.866,84 | -€919,59 |
| 10 | Take profit fisso +€75 | -€3.935,91 | -€988,66 |
| 11 | Trailing 20% dopo +€50 | -€4.611,06 | -€1.663,81 |
| 12 | TP +€50 / SL -€50 | -€5.776,80 | -€2.829,55 |
| 13 | Take profit fisso +€25 | -€7.297,89 | -€4.350,64 |
| 14 | Take profit fisso +€50 | -€7.811,16 | -€4.863,91 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
