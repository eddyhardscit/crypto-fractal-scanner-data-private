# Analisi uscite paper trading a leva

Generato: 2026-08-10T23:59:39+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3662**
- Trade con percorso cronologico utilizzabile: **3608**
- Trade che hanno raggiunto almeno +€50: **1409**
- Di questi, chiusi poi in perdita: **291**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€4.098,57 | +€12.333,21 |
| 2 | Chiude 50% a +€50 | -€4.967,09 | +€3.267,56 |
| 3 | Protegge +€30 dopo +€50 | -€6.463,83 | +€1.770,81 |
| 4 | TP +€50 / SL -€50 | -€6.519,97 | +€1.714,67 |
| 5 | Protegge +€20 dopo +€50 | -€7.400,12 | +€834,52 |
| 6 | Trailing 20% dopo +€50 | -€8.080,48 | +€154,16 |
| 7 | Strategia attuale | -€8.234,64 | €0,00 |
| 8 | Take profit fisso +€200 | -€8.234,64 | €0,00 |
| 9 | Take profit fisso +€150 | -€8.238,96 | -€4,32 |
| 10 | Take profit fisso +€100 | -€8.449,88 | -€215,24 |
| 11 | Pareggio dopo +€50 | -€9.356,63 | -€1.121,99 |
| 12 | Take profit fisso +€75 | -€11.644,78 | -€3.410,13 |
| 13 | Take profit fisso +€25 | -€18.640,38 | -€10.405,73 |
| 14 | Take profit fisso +€50 | -€18.714,13 | -€10.479,49 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
