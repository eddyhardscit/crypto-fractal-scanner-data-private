# Analisi uscite paper trading a leva

Generato: 2026-07-26T10:54:18+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1889**
- Trade con percorso cronologico utilizzabile: **1835**
- Trade che hanno raggiunto almeno +€50: **872**
- Di questi, chiusi poi in perdita: **182**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.762,09 | +€8.786,15 |
| 2 | Chiude 50% a +€50 | +€801,93 | +€826,00 |
| 3 | Protegge +€30 dopo +€50 | +€510,58 | +€534,65 |
| 4 | Protegge +€20 dopo +€50 | +€301,05 | +€325,11 |
| 5 | Strategia attuale | -€24,07 | €0,00 |
| 6 | Take profit fisso +€200 | -€24,07 | €0,00 |
| 7 | Take profit fisso +€150 | -€24,80 | -€0,74 |
| 8 | Take profit fisso +€100 | -€88,77 | -€64,70 |
| 9 | TP +€50 / SL -€50 | -€294,84 | -€270,78 |
| 10 | Trailing 20% dopo +€50 | -€744,72 | -€720,65 |
| 11 | Pareggio dopo +€50 | -€880,33 | -€856,27 |
| 12 | Take profit fisso +€75 | -€3.122,64 | -€3.098,57 |
| 13 | Take profit fisso +€50 | -€8.942,86 | -€8.918,80 |
| 14 | Take profit fisso +€25 | -€13.361,71 | -€13.337,65 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
