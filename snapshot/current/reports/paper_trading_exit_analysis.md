# Analisi uscite paper trading a leva

Generato: 2026-07-26T09:39:20+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1886**
- Trade con percorso cronologico utilizzabile: **1832**
- Trade che hanno raggiunto almeno +€50: **872**
- Di questi, chiusi poi in perdita: **182**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.863,54 | +€8.784,41 |
| 2 | Chiude 50% a +€50 | +€905,12 | +€826,00 |
| 3 | Protegge +€30 dopo +€50 | +€613,77 | +€534,65 |
| 4 | Protegge +€20 dopo +€50 | +€404,23 | +€325,11 |
| 5 | Strategia attuale | +€79,12 | €0,00 |
| 6 | Take profit fisso +€200 | +€79,12 | €0,00 |
| 7 | Take profit fisso +€150 | +€78,38 | -€0,74 |
| 8 | Take profit fisso +€100 | +€14,42 | -€64,70 |
| 9 | TP +€50 / SL -€50 | -€193,39 | -€272,51 |
| 10 | Trailing 20% dopo +€50 | -€641,53 | -€720,65 |
| 11 | Pareggio dopo +€50 | -€777,14 | -€856,27 |
| 12 | Take profit fisso +€75 | -€3.019,45 | -€3.098,57 |
| 13 | Take profit fisso +€50 | -€8.839,68 | -€8.918,80 |
| 14 | Take profit fisso +€25 | -€13.258,52 | -€13.337,65 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
