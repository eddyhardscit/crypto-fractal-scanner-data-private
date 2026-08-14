# Analisi uscite paper trading a leva

Generato: 2026-08-14T00:21:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4833**
- Trade con percorso cronologico utilizzabile: **4779**
- Trade che hanno raggiunto almeno +€50: **1810**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.735,71 | +€18.376,74 |
| 2 | TP +€50 / SL -€50 | -€17.266,97 | +€5.845,48 |
| 3 | Protegge +€30 dopo +€50 | -€18.601,86 | +€4.510,59 |
| 4 | Chiude 50% a +€50 | -€19.591,98 | +€3.520,47 |
| 5 | Protegge +€20 dopo +€50 | -€20.833,09 | +€2.279,36 |
| 6 | Strategia attuale | -€23.112,45 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.112,45 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.116,77 | -€4,32 |
| 9 | Take profit fisso +€100 | -€23.667,23 | -€554,78 |
| 10 | Trailing 20% dopo +€50 | -€23.788,79 | -€676,34 |
| 11 | Pareggio dopo +€50 | -€24.615,46 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.198,03 | -€5.085,58 |
| 13 | Take profit fisso +€50 | -€35.451,00 | -€12.338,55 |
| 14 | Take profit fisso +€25 | -€40.790,16 | -€17.677,71 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
