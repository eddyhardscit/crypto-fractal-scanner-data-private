# Analisi uscite paper trading a leva

Generato: 2026-07-26T00:39:42+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1572**
- Trade con percorso cronologico utilizzabile: **1518**
- Trade che hanno raggiunto almeno +€50: **741**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.450,67 | +€4.254,39 |
| 2 | Chiude 50% a +€50 | +€3.083,13 | +€886,85 |
| 3 | Protegge +€20 dopo +€50 | +€2.240,63 | +€44,35 |
| 4 | Strategia attuale | +€2.196,28 | €0,00 |
| 5 | Take profit fisso +€200 | +€2.196,28 | €0,00 |
| 6 | Take profit fisso +€150 | +€2.195,54 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€2.170,06 | -€26,22 |
| 8 | Take profit fisso +€100 | +€2.159,64 | -€36,63 |
| 9 | Pareggio dopo +€50 | +€1.315,44 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€697,25 | -€1.499,03 |
| 11 | Take profit fisso +€75 | -€354,42 | -€2.550,69 |
| 12 | TP +€50 / SL -€50 | -€1.764,56 | -€3.960,84 |
| 13 | Take profit fisso +€50 | -€5.880,82 | -€8.077,10 |
| 14 | Take profit fisso +€25 | -€8.355,90 | -€10.552,18 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
