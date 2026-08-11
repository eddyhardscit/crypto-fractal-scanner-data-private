# Analisi uscite paper trading a leva

Generato: 2026-08-11T14:14:57+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3793**
- Trade con percorso cronologico utilizzabile: **3739**
- Trade che hanno raggiunto almeno +€50: **1492**
- Di questi, chiusi poi in perdita: **297**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.377,01 | +€12.514,85 |
| 2 | Chiude 50% a +€50 | -€1.690,72 | +€2.447,11 |
| 3 | Protegge +€30 dopo +€50 | -€1.882,94 | +€2.254,90 |
| 4 | Protegge +€20 dopo +€50 | -€2.933,09 | +€1.204,74 |
| 5 | TP +€50 / SL -€50 | -€3.973,67 | +€164,16 |
| 6 | Strategia attuale | -€4.137,83 | €0,00 |
| 7 | Take profit fisso +€200 | -€4.137,83 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.142,15 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€4.294,99 | -€157,16 |
| 10 | Take profit fisso +€100 | -€4.421,89 | -€284,06 |
| 11 | Pareggio dopo +€50 | -€5.047,17 | -€909,34 |
| 12 | Take profit fisso +€75 | -€8.514,88 | -€4.377,05 |
| 13 | Take profit fisso +€50 | -€16.349,47 | -€12.211,64 |
| 14 | Take profit fisso +€25 | -€18.154,46 | -€14.016,63 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
