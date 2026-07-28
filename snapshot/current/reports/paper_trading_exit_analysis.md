# Analisi uscite paper trading a leva

Generato: 2026-07-28T12:40:07+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2941**
- Trade con percorso cronologico utilizzabile: **2887**
- Trade che hanno raggiunto almeno +€50: **1266**
- Di questi, chiusi poi in perdita: **270**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.684,43 | +€10.963,81 |
| 2 | Chiude 50% a +€50 | +€757,15 | +€2.036,53 |
| 3 | Protegge +€30 dopo +€50 | +€176,24 | +€1.455,63 |
| 4 | Protegge +€20 dopo +€50 | -€707,20 | +€572,18 |
| 5 | Strategia attuale | -€1.279,38 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.279,38 | €0,00 |
| 7 | Take profit fisso +€150 | -€1.283,70 | -€4,32 |
| 8 | Take profit fisso +€100 | -€1.391,99 | -€112,61 |
| 9 | TP +€50 / SL -€50 | -€1.587,92 | -€308,54 |
| 10 | Trailing 20% dopo +€50 | -€1.624,04 | -€344,66 |
| 11 | Pareggio dopo +€50 | -€2.195,98 | -€916,60 |
| 12 | Take profit fisso +€75 | -€5.592,12 | -€4.312,74 |
| 13 | Take profit fisso +€50 | -€12.413,60 | -€11.134,22 |
| 14 | Take profit fisso +€25 | -€13.619,42 | -€12.340,03 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
