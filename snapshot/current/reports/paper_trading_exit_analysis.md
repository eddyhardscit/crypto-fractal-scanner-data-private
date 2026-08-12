# Analisi uscite paper trading a leva

Generato: 2026-08-12T03:28:40+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4189**
- Trade con percorso cronologico utilizzabile: **4135**
- Trade che hanno raggiunto almeno +€50: **1621**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€1.882,24 | +€14.529,29 |
| 2 | Chiude 50% a +€50 | -€8.832,46 | +€3.814,58 |
| 3 | TP +€50 / SL -€50 | -€9.124,93 | +€3.522,11 |
| 4 | Protegge +€30 dopo +€50 | -€9.639,73 | +€3.007,32 |
| 5 | Protegge +€20 dopo +€50 | -€11.405,16 | +€1.241,89 |
| 6 | Strategia attuale | -€12.647,05 | €0,00 |
| 7 | Take profit fisso +€200 | -€12.647,05 | €0,00 |
| 8 | Take profit fisso +€150 | -€12.651,36 | -€4,32 |
| 9 | Take profit fisso +€100 | -€12.991,56 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€13.569,35 | -€922,31 |
| 11 | Pareggio dopo +€50 | -€14.661,52 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€16.457,67 | -€3.810,63 |
| 13 | Take profit fisso +€50 | -€23.500,20 | -€10.853,15 |
| 14 | Take profit fisso +€25 | -€26.677,18 | -€14.030,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
