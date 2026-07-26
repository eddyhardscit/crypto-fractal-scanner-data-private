# Analisi uscite paper trading a leva

Generato: 2026-07-26T12:54:17+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1898**
- Trade con percorso cronologico utilizzabile: **1844**
- Trade che hanno raggiunto almeno +€50: **876**
- Di questi, chiusi poi in perdita: **184**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.882,60 | +€8.786,15 |
| 2 | Chiude 50% a +€50 | +€947,29 | +€850,84 |
| 3 | Protegge +€30 dopo +€50 | +€538,86 | +€442,41 |
| 4 | Protegge +€20 dopo +€50 | +€309,32 | +€212,88 |
| 5 | Strategia attuale | +€96,44 | €0,00 |
| 6 | Take profit fisso +€200 | +€96,44 | €0,00 |
| 7 | Take profit fisso +€150 | +€95,71 | -€0,74 |
| 8 | Take profit fisso +€100 | +€31,74 | -€64,70 |
| 9 | TP +€50 / SL -€50 | -€226,57 | -€323,01 |
| 10 | Trailing 20% dopo +€50 | -€705,50 | -€801,95 |
| 11 | Pareggio dopo +€50 | -€759,82 | -€856,27 |
| 12 | Take profit fisso +€75 | -€3.004,63 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€8.874,59 | -€8.971,03 |
| 14 | Take profit fisso +€25 | -€13.343,44 | -€13.439,88 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
