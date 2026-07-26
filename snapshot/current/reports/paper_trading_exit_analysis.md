# Analisi uscite paper trading a leva

Generato: 2026-07-26T05:39:11+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1691**
- Trade con percorso cronologico utilizzabile: **1637**
- Trade che hanno raggiunto almeno +€50: **813**
- Di questi, chiusi poi in perdita: **175**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.949,80 | +€4.353,98 |
| 2 | Chiude 50% a +€50 | +€6.163,67 | +€567,85 |
| 3 | Protegge +€30 dopo +€50 | +€5.958,70 | +€362,89 |
| 4 | Protegge +€20 dopo +€50 | +€5.854,36 | +€258,54 |
| 5 | Strategia attuale | +€5.595,82 | €0,00 |
| 6 | Take profit fisso +€200 | +€5.595,82 | €0,00 |
| 7 | Take profit fisso +€150 | +€5.595,08 | -€0,74 |
| 8 | Take profit fisso +€100 | +€5.531,47 | -€64,35 |
| 9 | Pareggio dopo +€50 | +€4.734,44 | -€861,37 |
| 10 | Trailing 20% dopo +€50 | +€4.541,58 | -€1.054,24 |
| 11 | Take profit fisso +€75 | +€2.642,78 | -€2.953,03 |
| 12 | TP +€50 / SL -€50 | +€1.054,53 | -€4.541,28 |
| 13 | Take profit fisso +€50 | -€3.161,32 | -€8.757,13 |
| 14 | Take profit fisso +€25 | -€6.842,76 | -€12.438,58 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
