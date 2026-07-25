# Analisi uscite paper trading a leva

Generato: 2026-07-25T19:24:22+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1507**
- Trade con percorso cronologico utilizzabile: **1453**
- Trade che hanno raggiunto almeno +€50: **728**
- Di questi, chiusi poi in perdita: **157**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.071,96 | +€4.027,71 |
| 2 | Chiude 50% a +€50 | +€4.549,65 | +€505,41 |
| 3 | Protegge +€20 dopo +€50 | +€4.088,59 | +€44,35 |
| 4 | Strategia attuale | +€4.044,25 | €0,00 |
| 5 | Take profit fisso +€200 | +€4.044,25 | €0,00 |
| 6 | Take profit fisso +€150 | +€4.043,51 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€4.012,60 | -€31,64 |
| 8 | Take profit fisso +€100 | +€4.007,61 | -€36,63 |
| 9 | Pareggio dopo +€50 | +€3.163,41 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€2.545,22 | -€1.499,03 |
| 11 | Take profit fisso +€75 | +€1.514,84 | -€2.529,41 |
| 12 | TP +€50 / SL -€50 | -€122,40 | -€4.166,65 |
| 13 | Take profit fisso +€50 | -€4.011,99 | -€8.056,23 |
| 14 | Take profit fisso +€25 | -€7.018,69 | -€11.062,93 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
