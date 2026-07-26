# Analisi uscite paper trading a leva

Generato: 2026-07-26T07:39:14+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1812**
- Trade con percorso cronologico utilizzabile: **1758**
- Trade che hanno raggiunto almeno +€50: **860**
- Di questi, chiusi poi in perdita: **177**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€10.362,56 | +€8.703,18 |
| 2 | Chiude 50% a +€50 | +€2.277,35 | +€617,97 |
| 3 | Protegge +€30 dopo +€50 | +€2.162,15 | +€502,77 |
| 4 | Protegge +€20 dopo +€50 | +€1.986,46 | +€327,08 |
| 5 | Strategia attuale | +€1.659,38 | €0,00 |
| 6 | Take profit fisso +€200 | +€1.659,38 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.658,64 | -€0,74 |
| 8 | Take profit fisso +€100 | +€1.594,68 | -€64,70 |
| 9 | TP +€50 / SL -€50 | +€1.148,71 | -€510,67 |
| 10 | Trailing 20% dopo +€50 | +€812,86 | -€846,52 |
| 11 | Pareggio dopo +€50 | +€803,11 | -€856,27 |
| 12 | Take profit fisso +€75 | -€1.470,27 | -€3.129,65 |
| 13 | Take profit fisso +€50 | -€7.416,34 | -€9.075,72 |
| 14 | Take profit fisso +€25 | -€11.821,14 | -€13.480,52 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
