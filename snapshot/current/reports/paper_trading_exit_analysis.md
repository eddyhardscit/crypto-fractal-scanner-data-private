# Analisi uscite paper trading a leva

Generato: 2026-08-11T22:29:31+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4154**
- Trade con percorso cronologico utilizzabile: **4100**
- Trade che hanno raggiunto almeno +€50: **1600**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€2.163,28 | +€14.507,34 |
| 2 | Chiude 50% a +€50 | -€8.866,80 | +€3.477,26 |
| 3 | TP +€50 / SL -€50 | -€8.948,03 | +€3.396,03 |
| 4 | Protegge +€30 dopo +€50 | -€9.382,56 | +€2.961,50 |
| 5 | Protegge +€20 dopo +€50 | -€11.111,49 | +€1.232,58 |
| 6 | Strategia attuale | -€12.344,06 | €0,00 |
| 7 | Take profit fisso +€200 | -€12.344,06 | €0,00 |
| 8 | Take profit fisso +€150 | -€12.348,38 | -€4,32 |
| 9 | Take profit fisso +€100 | -€12.688,58 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€13.328,94 | -€984,87 |
| 11 | Pareggio dopo +€50 | -€14.358,54 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€16.154,69 | -€3.810,63 |
| 13 | Take profit fisso +€50 | -€23.301,35 | -€10.957,29 |
| 14 | Take profit fisso +€25 | -€26.558,73 | -€14.214,66 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
