# Analisi uscite paper trading a leva

Generato: 2026-07-23T14:38:48+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **868**
- Trade con percorso cronologico utilizzabile: **814**
- Trade che hanno raggiunto almeno +€50: **340**
- Di questi, chiusi poi in perdita: **81**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.861,02 | +€1.672,87 |
| 2 | Chiude 50% a +€50 | -€4.134,07 | +€399,81 |
| 3 | Protegge +€20 dopo +€50 | -€4.199,25 | +€334,63 |
| 4 | Protegge +€30 dopo +€50 | -€4.340,30 | +€193,58 |
| 5 | Take profit fisso +€100 | -€4.344,05 | +€189,84 |
| 6 | Pareggio dopo +€50 | -€4.454,75 | +€79,13 |
| 7 | Strategia attuale | -€4.533,88 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.533,88 | €0,00 |
| 9 | Take profit fisso +€200 | -€4.533,88 | €0,00 |
| 10 | Take profit fisso +€75 | -€5.237,94 | -€704,06 |
| 11 | Trailing 20% dopo +€50 | -€5.248,42 | -€714,53 |
| 12 | TP +€50 / SL -€50 | -€6.794,64 | -€2.260,76 |
| 13 | Take profit fisso +€25 | -€7.134,27 | -€2.600,39 |
| 14 | Take profit fisso +€50 | -€8.483,51 | -€3.949,62 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
