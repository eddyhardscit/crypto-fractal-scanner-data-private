# Analisi uscite paper trading a leva

Generato: 2026-07-25T11:24:07+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1346**
- Trade con percorso cronologico utilizzabile: **1292**
- Trade che hanno raggiunto almeno +€50: **643**
- Di questi, chiusi poi in perdita: **144**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.238,90 | +€3.115,85 |
| 2 | Chiude 50% a +€50 | +€3.068,90 | +€945,85 |
| 3 | Take profit fisso +€100 | +€2.365,55 | +€242,51 |
| 4 | Strategia attuale | +€2.123,05 | €0,00 |
| 5 | Take profit fisso +€150 | +€2.123,05 | €0,00 |
| 6 | Take profit fisso +€200 | +€2.123,05 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | +€1.817,87 | -€305,17 |
| 8 | Protegge +€20 dopo +€50 | +€1.699,57 | -€423,47 |
| 9 | Pareggio dopo +€50 | +€1.003,92 | -€1.119,13 |
| 10 | Take profit fisso +€75 | +€742,09 | -€1.380,96 |
| 11 | Trailing 20% dopo +€50 | +€683,75 | -€1.439,29 |
| 12 | TP +€50 / SL -€50 | -€1.314,76 | -€3.437,81 |
| 13 | Take profit fisso +€50 | -€4.443,69 | -€6.566,73 |
| 14 | Take profit fisso +€25 | -€6.256,75 | -€8.379,79 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
