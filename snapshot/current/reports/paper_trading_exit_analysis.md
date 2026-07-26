# Analisi uscite paper trading a leva

Generato: 2026-07-26T01:39:05+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1578**
- Trade con percorso cronologico utilizzabile: **1524**
- Trade che hanno raggiunto almeno +€50: **746**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.763,49 | +€4.259,61 |
| 2 | Chiude 50% a +€50 | +€3.334,32 | +€830,44 |
| 3 | Protegge +€20 dopo +€50 | +€2.548,22 | +€44,35 |
| 4 | Strategia attuale | +€2.503,88 | €0,00 |
| 5 | Take profit fisso +€200 | +€2.503,88 | €0,00 |
| 6 | Take profit fisso +€150 | +€2.503,14 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€2.477,66 | -€26,22 |
| 8 | Take profit fisso +€100 | +€2.467,24 | -€36,63 |
| 9 | Pareggio dopo +€50 | +€1.623,04 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€1.004,85 | -€1.499,03 |
| 11 | Take profit fisso +€75 | -€46,82 | -€2.550,69 |
| 12 | TP +€50 / SL -€50 | -€1.564,56 | -€4.068,43 |
| 13 | Take profit fisso +€50 | -€5.686,04 | -€8.189,92 |
| 14 | Take profit fisso +€25 | -€8.286,12 | -€10.790,00 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
