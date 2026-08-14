# Analisi uscite paper trading a leva

Generato: 2026-08-14T04:11:56+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4921**
- Trade con percorso cronologico utilizzabile: **4867**
- Trade che hanno raggiunto almeno +€50: **1837**
- Di questi, chiusi poi in perdita: **351**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€5.080,54 | +€18.671,10 |
| 2 | TP +€50 / SL -€50 | -€17.006,40 | +€6.745,25 |
| 3 | Protegge +€30 dopo +€50 | -€18.964,78 | +€4.786,86 |
| 4 | Chiude 50% a +€50 | -€19.880,04 | +€3.871,61 |
| 5 | Protegge +€20 dopo +€50 | -€21.351,96 | +€2.399,69 |
| 6 | Strategia attuale | -€23.751,65 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.751,65 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.755,96 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€23.933,70 | -€182,06 |
| 10 | Take profit fisso +€100 | -€24.270,57 | -€518,92 |
| 11 | Pareggio dopo +€50 | -€25.251,26 | -€1.499,61 |
| 12 | Take profit fisso +€75 | -€28.742,55 | -€4.990,91 |
| 13 | Take profit fisso +€50 | -€35.484,79 | -€11.733,14 |
| 14 | Take profit fisso +€25 | -€40.889,89 | -€17.138,24 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
