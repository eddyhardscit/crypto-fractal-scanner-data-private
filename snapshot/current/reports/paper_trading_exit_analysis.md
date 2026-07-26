# Analisi uscite paper trading a leva

Generato: 2026-07-26T11:54:18+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1895**
- Trade con percorso cronologico utilizzabile: **1841**
- Trade che hanno raggiunto almeno +€50: **876**
- Di questi, chiusi poi in perdita: **184**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.902,53 | +€8.786,15 |
| 2 | Chiude 50% a +€50 | +€967,22 | +€850,84 |
| 3 | Protegge +€30 dopo +€50 | +€558,79 | +€442,41 |
| 4 | Protegge +€20 dopo +€50 | +€329,25 | +€212,88 |
| 5 | Strategia attuale | +€116,37 | €0,00 |
| 6 | Take profit fisso +€200 | +€116,37 | €0,00 |
| 7 | Take profit fisso +€150 | +€115,63 | -€0,74 |
| 8 | Take profit fisso +€100 | +€51,67 | -€64,70 |
| 9 | TP +€50 / SL -€50 | -€206,64 | -€323,01 |
| 10 | Trailing 20% dopo +€50 | -€685,58 | -€801,95 |
| 11 | Pareggio dopo +€50 | -€739,89 | -€856,27 |
| 12 | Take profit fisso +€75 | -€2.984,70 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€8.854,66 | -€8.971,03 |
| 14 | Take profit fisso +€25 | -€13.323,51 | -€13.439,88 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
