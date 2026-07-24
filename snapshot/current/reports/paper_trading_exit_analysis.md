# Analisi uscite paper trading a leva

Generato: 2026-07-24T03:53:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1063**
- Trade con percorso cronologico utilizzabile: **1009**
- Trade che hanno raggiunto almeno +€50: **464**
- Di questi, chiusi poi in perdita: **103**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€159,44 | +€2.275,06 |
| 2 | Chiude 50% a +€50 | -€1.406,65 | +€708,98 |
| 3 | Take profit fisso +€100 | -€2.025,38 | +€90,24 |
| 4 | Protegge +€30 dopo +€50 | -€2.105,25 | +€10,38 |
| 5 | Strategia attuale | -€2.115,62 | €0,00 |
| 6 | Take profit fisso +€150 | -€2.115,62 | €0,00 |
| 7 | Take profit fisso +€200 | -€2.115,62 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€2.281,22 | -€165,59 |
| 9 | Take profit fisso +€75 | -€2.931,23 | -€815,61 |
| 10 | Pareggio dopo +€50 | -€3.021,01 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€3.053,05 | -€937,42 |
| 12 | TP +€50 / SL -€50 | -€4.310,19 | -€2.194,57 |
| 13 | Take profit fisso +€50 | -€6.601,25 | -€4.485,62 |
| 14 | Take profit fisso +€25 | -€6.820,62 | -€4.704,99 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
