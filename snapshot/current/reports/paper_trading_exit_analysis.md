# Analisi uscite paper trading a leva

Generato: 2026-07-26T18:54:22+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1998**
- Trade con percorso cronologico utilizzabile: **1944**
- Trade che hanno raggiunto almeno +€50: **901**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.135,90 | +€8.867,34 |
| 2 | Chiude 50% a +€50 | +€406,99 | +€1.138,42 |
| 3 | Protegge +€30 dopo +€50 | -€126,26 | +€605,18 |
| 4 | Protegge +€20 dopo +€50 | -€423,37 | +€308,07 |
| 5 | TP +€50 / SL -€50 | -€654,25 | +€77,19 |
| 6 | Strategia attuale | -€731,44 | €0,00 |
| 7 | Take profit fisso +€200 | -€731,44 | €0,00 |
| 8 | Take profit fisso +€150 | -€732,17 | -€0,74 |
| 9 | Take profit fisso +€100 | -€796,14 | -€64,70 |
| 10 | Trailing 20% dopo +€50 | -€1.292,45 | -€561,02 |
| 11 | Pareggio dopo +€50 | -€1.574,30 | -€842,87 |
| 12 | Take profit fisso +€75 | -€3.832,51 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€9.383,45 | -€8.652,02 |
| 14 | Take profit fisso +€25 | -€13.698,22 | -€12.966,79 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
