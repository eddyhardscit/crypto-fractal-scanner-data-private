# Analisi uscite paper trading a leva

Generato: 2026-07-25T23:39:14+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1550**
- Trade con percorso cronologico utilizzabile: **1496**
- Trade che hanno raggiunto almeno +€50: **741**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.547,53 | +€4.060,78 |
| 2 | Chiude 50% a +€50 | +€4.373,61 | +€886,85 |
| 3 | Protegge +€20 dopo +€50 | +€3.531,10 | +€44,35 |
| 4 | Strategia attuale | +€3.486,76 | €0,00 |
| 5 | Take profit fisso +€200 | +€3.486,76 | €0,00 |
| 6 | Take profit fisso +€150 | +€3.486,02 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€3.460,54 | -€26,22 |
| 8 | Take profit fisso +€100 | +€3.450,12 | -€36,63 |
| 9 | Pareggio dopo +€50 | +€2.605,92 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€1.987,73 | -€1.499,03 |
| 11 | Take profit fisso +€75 | +€936,06 | -€2.550,69 |
| 12 | TP +€50 / SL -€50 | -€667,69 | -€4.154,45 |
| 13 | Take profit fisso +€50 | -€4.590,34 | -€8.077,10 |
| 14 | Take profit fisso +€25 | -€7.317,61 | -€10.804,37 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
