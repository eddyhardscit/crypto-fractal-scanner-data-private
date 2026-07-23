# Analisi uscite paper trading a leva

Generato: 2026-07-23T01:23:49+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **820**
- Trade con percorso cronologico utilizzabile: **766**
- Trade che hanno raggiunto almeno +€50: **321**
- Di questi, chiusi poi in perdita: **75**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.739,08 | +€1.565,34 |
| 2 | Protegge +€30 dopo +€50 | -€3.797,87 | +€506,54 |
| 3 | Chiude 50% a +€50 | -€3.969,62 | +€334,80 |
| 4 | Protegge +€20 dopo +€50 | -€4.021,31 | +€283,11 |
| 5 | Take profit fisso +€100 | -€4.110,46 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€4.236,81 | +€67,61 |
| 7 | Strategia attuale | -€4.304,42 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.304,42 | €0,00 |
| 9 | Take profit fisso +€200 | -€4.304,42 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.766,17 | -€461,75 |
| 11 | Take profit fisso +€75 | -€4.959,64 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€6.437,90 | -€2.133,48 |
| 13 | Take profit fisso +€25 | -€6.959,03 | -€2.654,61 |
| 14 | Take profit fisso +€50 | -€8.019,24 | -€3.714,82 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
