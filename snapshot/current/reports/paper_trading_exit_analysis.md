# Analisi uscite paper trading a leva

Generato: 2026-07-26T21:54:22+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2001**
- Trade con percorso cronologico utilizzabile: **1947**
- Trade che hanno raggiunto almeno +€50: **901**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.125,07 | +€8.867,34 |
| 2 | Chiude 50% a +€50 | +€396,16 | +€1.138,42 |
| 3 | Protegge +€30 dopo +€50 | -€137,08 | +€605,18 |
| 4 | Protegge +€20 dopo +€50 | -€434,20 | +€308,07 |
| 5 | TP +€50 / SL -€50 | -€665,07 | +€77,19 |
| 6 | Strategia attuale | -€742,26 | €0,00 |
| 7 | Take profit fisso +€200 | -€742,26 | €0,00 |
| 8 | Take profit fisso +€150 | -€743,00 | -€0,74 |
| 9 | Take profit fisso +€100 | -€806,97 | -€64,70 |
| 10 | Trailing 20% dopo +€50 | -€1.303,28 | -€561,02 |
| 11 | Pareggio dopo +€50 | -€1.585,13 | -€842,87 |
| 12 | Take profit fisso +€75 | -€3.843,34 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€9.394,28 | -€8.652,02 |
| 14 | Take profit fisso +€25 | -€13.709,05 | -€12.966,79 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
