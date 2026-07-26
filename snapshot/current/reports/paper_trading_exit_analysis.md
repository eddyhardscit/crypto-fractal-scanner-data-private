# Analisi uscite paper trading a leva

Generato: 2026-07-26T19:54:21+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1999**
- Trade con percorso cronologico utilizzabile: **1945**
- Trade che hanno raggiunto almeno +€50: **901**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.133,23 | +€8.867,34 |
| 2 | Chiude 50% a +€50 | +€404,32 | +€1.138,42 |
| 3 | Protegge +€30 dopo +€50 | -€128,93 | +€605,18 |
| 4 | Protegge +€20 dopo +€50 | -€426,04 | +€308,07 |
| 5 | TP +€50 / SL -€50 | -€656,92 | +€77,19 |
| 6 | Strategia attuale | -€734,11 | €0,00 |
| 7 | Take profit fisso +€200 | -€734,11 | €0,00 |
| 8 | Take profit fisso +€150 | -€734,85 | -€0,74 |
| 9 | Take profit fisso +€100 | -€798,81 | -€64,70 |
| 10 | Trailing 20% dopo +€50 | -€1.295,12 | -€561,02 |
| 11 | Pareggio dopo +€50 | -€1.576,97 | -€842,87 |
| 12 | Take profit fisso +€75 | -€3.835,18 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€9.386,12 | -€8.652,02 |
| 14 | Take profit fisso +€25 | -€13.700,89 | -€12.966,79 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
