# Analisi uscite paper trading a leva

Generato: 2026-07-27T23:24:49+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2697**
- Trade con percorso cronologico utilizzabile: **2643**
- Trade che hanno raggiunto almeno +€50: **1175**
- Di questi, chiusi poi in perdita: **237**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.672,94 | +€9.780,27 |
| 2 | Chiude 50% a +€50 | +€530,60 | +€1.637,93 |
| 3 | Protegge +€30 dopo +€50 | +€500,58 | +€1.607,91 |
| 4 | Protegge +€20 dopo +€50 | -€587,35 | +€519,98 |
| 5 | Strategia attuale | -€1.107,33 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.107,33 | €0,00 |
| 7 | Take profit fisso +€100 | -€1.109,56 | -€2,23 |
| 8 | Take profit fisso +€150 | -€1.111,65 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€1.119,24 | -€11,91 |
| 10 | Pareggio dopo +€50 | -€1.680,24 | -€572,91 |
| 11 | TP +€50 / SL -€50 | -€1.701,32 | -€593,99 |
| 12 | Take profit fisso +€75 | -€4.814,09 | -€3.706,76 |
| 13 | Take profit fisso +€50 | -€11.343,46 | -€10.236,13 |
| 14 | Take profit fisso +€25 | -€13.875,74 | -€12.768,41 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
