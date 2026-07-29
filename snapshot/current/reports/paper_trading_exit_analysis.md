# Analisi uscite paper trading a leva

Generato: 2026-07-29T23:25:16+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3400**
- Trade con percorso cronologico utilizzabile: **3346**
- Trade che hanno raggiunto almeno +€50: **1381**
- Di questi, chiusi poi in perdita: **277**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.173,71 | +€11.994,48 |
| 2 | Chiude 50% a +€50 | -€4.066,78 | +€2.753,99 |
| 3 | Protegge +€30 dopo +€50 | -€5.465,39 | +€1.355,38 |
| 4 | Protegge +€20 dopo +€50 | -€6.248,21 | +€572,56 |
| 5 | TP +€50 / SL -€50 | -€6.320,70 | +€500,07 |
| 6 | Strategia attuale | -€6.820,77 | €0,00 |
| 7 | Take profit fisso +€200 | -€6.820,77 | €0,00 |
| 8 | Take profit fisso +€150 | -€6.825,09 | -€4,32 |
| 9 | Take profit fisso +€100 | -€7.036,01 | -€215,24 |
| 10 | Trailing 20% dopo +€50 | -€7.325,98 | -€505,21 |
| 11 | Pareggio dopo +€50 | -€7.948,49 | -€1.127,72 |
| 12 | Take profit fisso +€75 | -€10.956,34 | -€4.135,56 |
| 13 | Take profit fisso +€25 | -€18.023,83 | -€11.203,06 |
| 14 | Take profit fisso +€50 | -€18.176,13 | -€11.355,36 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
