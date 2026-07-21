# Analisi uscite paper trading a leva

Generato: 2026-07-21T21:53:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **584**
- Trade con percorso cronologico utilizzabile: **530**
- Trade che hanno raggiunto almeno +€50: **253**
- Di questi, chiusi poi in perdita: **62**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€999,07 | +€894,36 |
| 2 | Protegge +€30 dopo +€50 | +€695,51 | +€590,80 |
| 3 | Protegge +€20 dopo +€50 | +€434,92 | +€330,22 |
| 4 | Chiude 50% a +€50 | +€385,41 | +€280,71 |
| 5 | Take profit fisso +€100 | +€291,07 | +€186,37 |
| 6 | Pareggio dopo +€50 | +€172,31 | +€67,61 |
| 7 | Strategia attuale | +€104,70 | €0,00 |
| 8 | Take profit fisso +€150 | +€104,70 | €0,00 |
| 9 | Take profit fisso +€200 | +€104,70 | €0,00 |
| 10 | Take profit fisso +€75 | -€356,65 | -€461,35 |
| 11 | Trailing 20% dopo +€50 | -€359,57 | -€464,28 |
| 12 | TP +€50 / SL -€50 | -€1.697,26 | -€1.801,96 |
| 13 | Take profit fisso +€50 | -€2.607,61 | -€2.712,32 |
| 14 | Take profit fisso +€25 | -€2.914,12 | -€3.018,82 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
