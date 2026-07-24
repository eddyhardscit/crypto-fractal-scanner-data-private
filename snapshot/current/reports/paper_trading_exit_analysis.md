# Analisi uscite paper trading a leva

Generato: 2026-07-24T01:53:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1010**
- Trade con percorso cronologico utilizzabile: **956**
- Trade che hanno raggiunto almeno +€50: **439**
- Di questi, chiusi poi in perdita: **96**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€851,17 | +€2.034,00 |
| 2 | Chiude 50% a +€50 | -€937,04 | +€245,79 |
| 3 | Take profit fisso +€100 | -€1.092,59 | +€90,24 |
| 4 | Strategia attuale | -€1.182,83 | €0,00 |
| 5 | Take profit fisso +€150 | -€1.182,83 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.182,83 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€1.406,90 | -€224,06 |
| 8 | Protegge +€20 dopo +€50 | -€1.447,31 | -€264,48 |
| 9 | Pareggio dopo +€50 | -€2.088,22 | -€905,38 |
| 10 | Take profit fisso +€75 | -€2.099,74 | -€916,90 |
| 11 | Trailing 20% dopo +€50 | -€2.540,07 | -€1.357,24 |
| 12 | TP +€50 / SL -€50 | -€4.092,82 | -€2.909,99 |
| 13 | Take profit fisso +€50 | -€6.142,82 | -€4.959,98 |
| 14 | Take profit fisso +€25 | -€6.326,82 | -€5.143,99 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
