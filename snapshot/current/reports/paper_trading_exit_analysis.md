# Analisi uscite paper trading a leva

Generato: 2026-07-24T00:53:51+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **976**
- Trade con percorso cronologico utilizzabile: **922**
- Trade che hanno raggiunto almeno +€50: **408**
- Di questi, chiusi poi in perdita: **90**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€450,32 | +€2.028,40 |
| 2 | Chiude 50% a +€50 | -€2.314,61 | +€164,12 |
| 3 | Take profit fisso +€100 | -€2.376,88 | +€101,85 |
| 4 | Strategia attuale | -€2.478,72 | €0,00 |
| 5 | Take profit fisso +€150 | -€2.478,72 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.478,72 | €0,00 |
| 7 | Protegge +€20 dopo +€50 | -€2.821,80 | -€343,07 |
| 8 | Protegge +€30 dopo +€50 | -€2.858,91 | -€380,18 |
| 9 | Take profit fisso +€75 | -€3.378,13 | -€899,40 |
| 10 | Pareggio dopo +€50 | -€3.396,43 | -€917,70 |
| 11 | Trailing 20% dopo +€50 | -€4.078,92 | -€1.600,20 |
| 12 | TP +€50 / SL -€50 | -€5.392,70 | -€2.913,98 |
| 13 | Take profit fisso +€25 | -€7.011,06 | -€4.532,34 |
| 14 | Take profit fisso +€50 | -€7.437,10 | -€4.958,37 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
