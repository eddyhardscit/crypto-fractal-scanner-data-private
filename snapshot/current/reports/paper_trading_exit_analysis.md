# Analisi uscite paper trading a leva

Generato: 2026-07-19T03:53:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **233**
- Trade con percorso cronologico utilizzabile: **179**
- Trade che hanno raggiunto almeno +€50: **99**
- Di questi, chiusi poi in perdita: **18**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.923,06 | +€234,80 |
| 2 | Protegge +€20 dopo +€50 | +€1.830,79 | +€142,53 |
| 3 | Stop loss fisso -€50 | +€1.805,82 | +€117,56 |
| 4 | Pareggio dopo +€50 | +€1.742,90 | +€54,64 |
| 5 | Strategia attuale | +€1.688,26 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.688,26 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.688,26 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.656,23 | -€32,03 |
| 9 | Chiude 50% a +€50 | +€1.359,54 | -€328,72 |
| 10 | Trailing 20% dopo +€50 | +€1.233,98 | -€454,28 |
| 11 | Take profit fisso +€75 | +€1.020,07 | -€668,19 |
| 12 | TP +€50 / SL -€50 | +€294,82 | -€1.393,44 |
| 13 | Take profit fisso +€50 | +€161,26 | -€1.527,00 |
| 14 | Take profit fisso +€25 | -€416,54 | -€2.104,80 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
