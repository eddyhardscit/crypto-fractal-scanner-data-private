# Analisi uscite paper trading a leva

Generato: 2026-07-25T15:24:13+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1435**
- Trade con percorso cronologico utilizzabile: **1381**
- Trade che hanno raggiunto almeno +€50: **701**
- Di questi, chiusi poi in perdita: **145**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.623,14 | +€3.225,52 |
| 2 | Strategia attuale | +€6.397,62 | €0,00 |
| 3 | Take profit fisso +€200 | +€6.397,62 | €0,00 |
| 4 | Take profit fisso +€150 | +€6.396,88 | -€0,74 |
| 5 | Take profit fisso +€100 | +€6.360,99 | -€36,63 |
| 6 | Chiude 50% a +€50 | +€6.154,71 | -€242,91 |
| 7 | Protegge +€20 dopo +€50 | +€5.991,86 | -€405,76 |
| 8 | Protegge +€30 dopo +€50 | +€5.841,20 | -€556,42 |
| 9 | Pareggio dopo +€50 | +€5.278,49 | -€1.119,13 |
| 10 | Trailing 20% dopo +€50 | +€4.150,46 | -€2.247,16 |
| 11 | Take profit fisso +€75 | +€3.815,05 | -€2.582,57 |
| 12 | TP +€50 / SL -€50 | +€628,66 | -€5.768,96 |
| 13 | Take profit fisso +€50 | -€2.609,94 | -€9.007,55 |
| 14 | Take profit fisso +€25 | -€5.759,37 | -€12.156,99 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
