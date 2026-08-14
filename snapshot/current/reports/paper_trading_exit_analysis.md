# Analisi uscite paper trading a leva

Generato: 2026-08-14T03:12:12+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4890**
- Trade con percorso cronologico utilizzabile: **4836**
- Trade che hanno raggiunto almeno +€50: **1825**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.700,23 | +€18.546,71 |
| 2 | TP +€50 / SL -€50 | -€17.193,20 | +€6.053,74 |
| 3 | Protegge +€30 dopo +€50 | -€18.787,19 | +€4.459,76 |
| 4 | Chiude 50% a +€50 | -€19.658,89 | +€3.588,05 |
| 5 | Protegge +€20 dopo +€50 | -€21.054,36 | +€2.192,58 |
| 6 | Strategia attuale | -€23.246,94 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.246,94 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.251,26 | -€4,32 |
| 9 | Take profit fisso +€100 | -€23.765,86 | -€518,92 |
| 10 | Trailing 20% dopo +€50 | -€23.833,73 | -€586,79 |
| 11 | Pareggio dopo +€50 | -€24.749,95 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.309,30 | -€5.062,36 |
| 13 | Take profit fisso +€50 | -€35.547,19 | -€12.300,25 |
| 14 | Take profit fisso +€25 | -€40.652,29 | -€17.405,35 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
