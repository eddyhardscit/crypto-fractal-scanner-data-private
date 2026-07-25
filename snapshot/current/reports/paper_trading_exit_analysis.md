# Analisi uscite paper trading a leva

Generato: 2026-07-25T14:31:38+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1376**
- Trade con percorso cronologico utilizzabile: **1322**
- Trade che hanno raggiunto almeno +€50: **656**
- Di questi, chiusi poi in perdita: **144**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.342,03 | +€3.210,27 |
| 2 | Chiude 50% a +€50 | +€2.980,36 | +€848,61 |
| 3 | Take profit fisso +€100 | +€2.374,26 | +€242,51 |
| 4 | Strategia attuale | +€2.131,76 | €0,00 |
| 5 | Take profit fisso +€150 | +€2.131,76 | €0,00 |
| 6 | Take profit fisso +€200 | +€2.131,76 | €0,00 |
| 7 | Protegge +€20 dopo +€50 | +€1.726,00 | -€405,76 |
| 8 | Protegge +€30 dopo +€50 | +€1.640,34 | -€491,42 |
| 9 | Pareggio dopo +€50 | +€1.012,63 | -€1.119,13 |
| 10 | Take profit fisso +€75 | +€749,77 | -€1.381,99 |
| 11 | Trailing 20% dopo +€50 | +€320,70 | -€1.811,06 |
| 12 | TP +€50 / SL -€50 | -€1.406,13 | -€3.537,88 |
| 13 | Take profit fisso +€50 | -€4.629,47 | -€6.761,23 |
| 14 | Take profit fisso +€25 | -€6.767,53 | -€8.899,29 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
