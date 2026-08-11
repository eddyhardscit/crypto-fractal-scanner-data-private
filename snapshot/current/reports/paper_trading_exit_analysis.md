# Analisi uscite paper trading a leva

Generato: 2026-08-11T18:14:12+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4015**
- Trade con percorso cronologico utilizzabile: **3961**
- Trade che hanno raggiunto almeno +€50: **1580**
- Di questi, chiusi poi in perdita: **297**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.635,44 | +€13.898,09 |
| 2 | Chiude 50% a +€50 | -€4.411,43 | +€2.851,22 |
| 3 | Protegge +€30 dopo +€50 | -€5.178,65 | +€2.084,00 |
| 4 | TP +€50 / SL -€50 | -€5.498,26 | +€1.764,39 |
| 5 | Protegge +€20 dopo +€50 | -€6.776,38 | +€486,27 |
| 6 | Strategia attuale | -€7.262,65 | €0,00 |
| 7 | Take profit fisso +€200 | -€7.262,65 | €0,00 |
| 8 | Take profit fisso +€150 | -€7.266,97 | -€4,32 |
| 9 | Take profit fisso +€100 | -€7.607,16 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€8.840,14 | -€1.577,49 |
| 11 | Pareggio dopo +€50 | -€9.763,43 | -€2.500,78 |
| 12 | Take profit fisso +€75 | -€11.213,23 | -€3.950,58 |
| 13 | Take profit fisso +€50 | -€19.257,29 | -€11.994,65 |
| 14 | Take profit fisso +€25 | -€22.549,94 | -€15.287,29 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
