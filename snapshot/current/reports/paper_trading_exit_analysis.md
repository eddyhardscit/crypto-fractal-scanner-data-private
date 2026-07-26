# Analisi uscite paper trading a leva

Generato: 2026-07-26T17:54:21+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1996**
- Trade con percorso cronologico utilizzabile: **1942**
- Trade che hanno raggiunto almeno +€50: **899**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.048,17 | +€8.867,34 |
| 2 | Chiude 50% a +€50 | +€313,12 | +€1.132,29 |
| 3 | Protegge +€30 dopo +€50 | -€213,99 | +€605,18 |
| 4 | Protegge +€20 dopo +€50 | -€511,10 | +€308,07 |
| 5 | TP +€50 / SL -€50 | -€754,25 | +€64,92 |
| 6 | Strategia attuale | -€819,17 | €0,00 |
| 7 | Take profit fisso +€200 | -€819,17 | €0,00 |
| 8 | Take profit fisso +€150 | -€819,91 | -€0,74 |
| 9 | Take profit fisso +€100 | -€883,87 | -€64,70 |
| 10 | Trailing 20% dopo +€50 | -€1.387,87 | -€568,70 |
| 11 | Pareggio dopo +€50 | -€1.662,03 | -€842,87 |
| 12 | Take profit fisso +€75 | -€3.920,24 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€9.483,45 | -€8.664,28 |
| 14 | Take profit fisso +€25 | -€13.748,22 | -€12.929,06 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
