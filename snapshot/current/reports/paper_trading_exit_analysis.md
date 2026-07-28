# Analisi uscite paper trading a leva

Generato: 2026-07-28T13:39:59+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2962**
- Trade con percorso cronologico utilizzabile: **2908**
- Trade che hanno raggiunto almeno +€50: **1269**
- Di questi, chiusi poi in perdita: **270**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.389,40 | +€11.085,37 |
| 2 | Chiude 50% a +€50 | +€276,72 | +€1.972,68 |
| 3 | Protegge +€30 dopo +€50 | -€422,35 | +€1.273,61 |
| 4 | Protegge +€20 dopo +€50 | -€1.123,78 | +€572,18 |
| 5 | Strategia attuale | -€1.695,96 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.695,96 | €0,00 |
| 7 | Take profit fisso +€150 | -€1.700,28 | -€4,32 |
| 8 | Take profit fisso +€100 | -€1.850,59 | -€154,62 |
| 9 | TP +€50 / SL -€50 | -€2.010,65 | -€314,69 |
| 10 | Trailing 20% dopo +€50 | -€2.184,83 | -€488,87 |
| 11 | Pareggio dopo +€50 | -€2.612,56 | -€916,60 |
| 12 | Take profit fisso +€75 | -€6.100,72 | -€4.404,76 |
| 13 | Take profit fisso +€50 | -€12.957,89 | -€11.261,92 |
| 14 | Take profit fisso +€25 | -€14.091,26 | -€12.395,30 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
