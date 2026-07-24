# Analisi uscite paper trading a leva

Generato: 2026-07-24T17:53:54+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1171**
- Trade con percorso cronologico utilizzabile: **1117**
- Trade che hanno raggiunto almeno +€50: **524**
- Di questi, chiusi poi in perdita: **124**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€70,40 | +€2.391,38 |
| 2 | Chiude 50% a +€50 | -€986,58 | +€1.475,20 |
| 3 | Take profit fisso +€100 | -€2.104,66 | +€357,12 |
| 4 | Strategia attuale | -€2.461,78 | €0,00 |
| 5 | Take profit fisso +€150 | -€2.461,78 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.461,78 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€2.514,91 | -€53,13 |
| 8 | Protegge +€20 dopo +€50 | -€2.701,84 | -€240,06 |
| 9 | Take profit fisso +€75 | -€3.086,79 | -€625,02 |
| 10 | Pareggio dopo +€50 | -€3.367,16 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€3.526,50 | -€1.064,73 |
| 12 | TP +€50 / SL -€50 | -€4.697,20 | -€2.235,42 |
| 13 | Take profit fisso +€25 | -€6.934,91 | -€4.473,13 |
| 14 | Take profit fisso +€50 | -€7.104,57 | -€4.642,79 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
