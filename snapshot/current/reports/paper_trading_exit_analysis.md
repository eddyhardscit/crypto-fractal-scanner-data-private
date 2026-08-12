# Analisi uscite paper trading a leva

Generato: 2026-08-12T15:43:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4554**
- Trade con percorso cronologico utilizzabile: **4500**
- Trade che hanno raggiunto almeno +€50: **1687**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€8.673,57 | +€16.398,53 |
| 2 | TP +€50 / SL -€50 | -€18.008,33 | +€7.063,77 |
| 3 | Chiude 50% a +€50 | -€20.005,43 | +€5.066,68 |
| 4 | Protegge +€30 dopo +€50 | -€20.576,45 | +€4.495,65 |
| 5 | Protegge +€20 dopo +€50 | -€22.687,67 | +€2.384,43 |
| 6 | Strategia attuale | -€25.072,10 | €0,00 |
| 7 | Take profit fisso +€200 | -€25.072,10 | €0,00 |
| 8 | Take profit fisso +€150 | -€25.076,42 | -€4,32 |
| 9 | Take profit fisso +€100 | -€25.416,62 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€25.510,03 | -€437,92 |
| 11 | Pareggio dopo +€50 | -€26.575,11 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.790,61 | -€3.718,50 |
| 13 | Take profit fisso +€50 | -€34.214,16 | -€9.142,05 |
| 14 | Take profit fisso +€25 | -€36.578,19 | -€11.506,08 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
