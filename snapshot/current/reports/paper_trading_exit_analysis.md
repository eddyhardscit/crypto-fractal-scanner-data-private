# Analisi uscite paper trading a leva

Generato: 2026-08-11T21:28:00+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4114**
- Trade con percorso cronologico utilizzabile: **4060**
- Trade che hanno raggiunto almeno +€50: **1597**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€3.273,00 | +€14.386,32 |
| 2 | Chiude 50% a +€50 | -€7.585,03 | +€3.528,29 |
| 3 | TP +€50 / SL -€50 | -€7.736,25 | +€3.377,07 |
| 4 | Protegge +€30 dopo +€50 | -€8.151,82 | +€2.961,50 |
| 5 | Protegge +€20 dopo +€50 | -€9.880,75 | +€1.232,58 |
| 6 | Strategia attuale | -€11.113,32 | €0,00 |
| 7 | Take profit fisso +€200 | -€11.113,32 | €0,00 |
| 8 | Take profit fisso +€150 | -€11.117,64 | -€4,32 |
| 9 | Take profit fisso +€100 | -€11.457,84 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€12.098,20 | -€984,87 |
| 11 | Pareggio dopo +€50 | -€13.127,80 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€14.889,13 | -€3.775,81 |
| 13 | Take profit fisso +€50 | -€21.968,55 | -€10.855,23 |
| 14 | Take profit fisso +€25 | -€25.471,47 | -€14.358,15 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
