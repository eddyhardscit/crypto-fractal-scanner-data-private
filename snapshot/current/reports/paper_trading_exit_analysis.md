# Analisi uscite paper trading a leva

Generato: 2026-07-24T16:53:55+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1162**
- Trade con percorso cronologico utilizzabile: **1108**
- Trade che hanno raggiunto almeno +€50: **515**
- Di questi, chiusi poi in perdita: **124**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€745,87 | +€2.391,38 |
| 2 | Chiude 50% a +€50 | -€1.549,32 | +€1.587,94 |
| 3 | Take profit fisso +€100 | -€2.780,13 | +€357,12 |
| 4 | Protegge +€30 dopo +€50 | -€3.125,91 | +€11,34 |
| 5 | Strategia attuale | -€3.137,25 | €0,00 |
| 6 | Take profit fisso +€150 | -€3.137,25 | €0,00 |
| 7 | Take profit fisso +€200 | -€3.137,25 | €0,00 |
| 8 | Protegge +€20 dopo +€50 | -€3.302,84 | -€165,59 |
| 9 | Take profit fisso +€75 | -€3.742,80 | -€605,55 |
| 10 | Pareggio dopo +€50 | -€4.042,64 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€4.152,79 | -€1.015,54 |
| 12 | TP +€50 / SL -€50 | -€5.147,20 | -€2.009,94 |
| 13 | Take profit fisso +€25 | -€7.159,91 | -€4.022,66 |
| 14 | Take profit fisso +€50 | -€7.554,57 | -€4.417,32 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
