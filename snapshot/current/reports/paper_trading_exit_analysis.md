# Analisi uscite paper trading a leva

Generato: 2026-08-12T04:28:37+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4190**
- Trade con percorso cronologico utilizzabile: **4136**
- Trade che hanno raggiunto almeno +€50: **1621**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€1.833,08 | +€14.529,29 |
| 2 | Chiude 50% a +€50 | -€8.881,63 | +€3.814,58 |
| 3 | TP +€50 / SL -€50 | -€9.174,10 | +€3.522,11 |
| 4 | Protegge +€30 dopo +€50 | -€9.688,89 | +€3.007,32 |
| 5 | Protegge +€20 dopo +€50 | -€11.454,32 | +€1.241,89 |
| 6 | Strategia attuale | -€12.696,21 | €0,00 |
| 7 | Take profit fisso +€200 | -€12.696,21 | €0,00 |
| 8 | Take profit fisso +€150 | -€12.700,53 | -€4,32 |
| 9 | Take profit fisso +€100 | -€13.040,73 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€13.618,52 | -€922,31 |
| 11 | Pareggio dopo +€50 | -€14.710,69 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€16.506,84 | -€3.810,63 |
| 13 | Take profit fisso +€50 | -€23.549,37 | -€10.853,15 |
| 14 | Take profit fisso +€25 | -€26.726,35 | -€14.030,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
