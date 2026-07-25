# Analisi uscite paper trading a leva

Generato: 2026-07-25T17:24:04+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1459**
- Trade con percorso cronologico utilizzabile: **1405**
- Trade che hanno raggiunto almeno +€50: **710**
- Di questi, chiusi poi in perdita: **148**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.136,21 | +€3.905,17 |
| 2 | Chiude 50% a +€50 | +€5.407,76 | +€176,72 |
| 3 | Strategia attuale | +€5.231,04 | €0,00 |
| 4 | Take profit fisso +€200 | +€5.231,04 | €0,00 |
| 5 | Take profit fisso +€150 | +€5.230,30 | -€0,74 |
| 6 | Take profit fisso +€100 | +€5.194,41 | -€36,63 |
| 7 | Protegge +€20 dopo +€50 | +€5.046,49 | -€184,56 |
| 8 | Protegge +€30 dopo +€50 | +€4.906,93 | -€324,12 |
| 9 | Pareggio dopo +€50 | +€4.313,12 | -€917,93 |
| 10 | Trailing 20% dopo +€50 | +€3.299,32 | -€1.931,72 |
| 11 | Take profit fisso +€75 | +€2.702,48 | -€2.528,56 |
| 12 | TP +€50 / SL -€50 | +€309,38 | -€4.921,67 |
| 13 | Take profit fisso +€50 | -€3.457,66 | -€8.688,71 |
| 14 | Take profit fisso +€25 | -€6.311,68 | -€11.542,72 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
