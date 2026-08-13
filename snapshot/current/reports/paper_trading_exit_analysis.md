# Analisi uscite paper trading a leva

Generato: 2026-08-13T22:14:54+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4825**
- Trade con percorso cronologico utilizzabile: **4771**
- Trade che hanno raggiunto almeno +€50: **1810**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.713,08 | +€18.376,74 |
| 2 | TP +€50 / SL -€50 | -€17.244,33 | +€5.845,48 |
| 3 | Protegge +€30 dopo +€50 | -€18.579,23 | +€4.510,59 |
| 4 | Chiude 50% a +€50 | -€19.569,35 | +€3.520,47 |
| 5 | Protegge +€20 dopo +€50 | -€20.810,46 | +€2.279,36 |
| 6 | Strategia attuale | -€23.089,82 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.089,82 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.094,13 | -€4,32 |
| 9 | Take profit fisso +€100 | -€23.644,59 | -€554,78 |
| 10 | Trailing 20% dopo +€50 | -€23.766,16 | -€676,34 |
| 11 | Pareggio dopo +€50 | -€24.592,83 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.175,40 | -€5.085,58 |
| 13 | Take profit fisso +€50 | -€35.428,36 | -€12.338,55 |
| 14 | Take profit fisso +€25 | -€40.767,52 | -€17.677,71 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
