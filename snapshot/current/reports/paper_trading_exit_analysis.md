# Analisi uscite paper trading a leva

Generato: 2026-07-28T11:39:56+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2914**
- Trade con percorso cronologico utilizzabile: **2860**
- Trade che hanno raggiunto almeno +€50: **1257**
- Di questi, chiusi poi in perdita: **261**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€10.463,33 | +€10.923,23 |
| 2 | Chiude 50% a +€50 | +€1.338,13 | +€1.798,03 |
| 3 | Protegge +€30 dopo +€50 | +€698,72 | +€1.158,62 |
| 4 | Protegge +€20 dopo +€50 | -€94,72 | +€365,18 |
| 5 | Strategia attuale | -€459,89 | €0,00 |
| 6 | Take profit fisso +€200 | -€459,89 | €0,00 |
| 7 | Take profit fisso +€150 | -€464,21 | -€4,32 |
| 8 | Take profit fisso +€100 | -€572,50 | -€112,61 |
| 9 | Trailing 20% dopo +€50 | -€1.023,04 | -€563,15 |
| 10 | TP +€50 / SL -€50 | -€1.286,02 | -€826,13 |
| 11 | Pareggio dopo +€50 | -€1.403,50 | -€943,61 |
| 12 | Take profit fisso +€75 | -€4.772,64 | -€4.312,74 |
| 13 | Take profit fisso +€50 | -€12.071,12 | -€11.611,23 |
| 14 | Take profit fisso +€25 | -€13.193,20 | -€12.733,31 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
