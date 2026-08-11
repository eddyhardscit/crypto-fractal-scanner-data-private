# Analisi uscite paper trading a leva

Generato: 2026-08-11T16:13:55+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3935**
- Trade con percorso cronologico utilizzabile: **3881**
- Trade che hanno raggiunto almeno +€50: **1518**
- Di questi, chiusi poi in perdita: **297**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€4.983,19 | +€13.826,86 |
| 2 | Chiude 50% a +€50 | -€6.410,82 | +€2.432,85 |
| 3 | Protegge +€30 dopo +€50 | -€6.556,01 | +€2.287,66 |
| 4 | Protegge +€20 dopo +€50 | -€7.623,74 | +€1.219,93 |
| 5 | TP +€50 / SL -€50 | -€7.822,99 | +€1.020,68 |
| 6 | Strategia attuale | -€8.843,67 | €0,00 |
| 7 | Take profit fisso +€200 | -€8.843,67 | €0,00 |
| 8 | Take profit fisso +€150 | -€8.847,99 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€8.986,00 | -€142,32 |
| 10 | Take profit fisso +€100 | -€9.134,65 | -€290,97 |
| 11 | Pareggio dopo +€50 | -€9.753,01 | -€909,34 |
| 12 | Take profit fisso +€75 | -€13.444,16 | -€4.600,49 |
| 13 | Take profit fisso +€50 | -€21.510,80 | -€12.667,13 |
| 14 | Take profit fisso +€25 | -€23.470,64 | -€14.626,97 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
