# Analisi uscite paper trading a leva

Generato: 2026-07-19T00:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **223**
- Trade con percorso cronologico utilizzabile: **169**
- Trade che hanno raggiunto almeno +€50: **96**
- Di questi, chiusi poi in perdita: **17**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.035,97 | +€234,80 |
| 2 | Protegge +€20 dopo +€50 | +€1.943,70 | +€142,53 |
| 3 | Stop loss fisso -€50 | +€1.908,94 | +€107,77 |
| 4 | Pareggio dopo +€50 | +€1.855,81 | +€54,64 |
| 5 | Strategia attuale | +€1.801,17 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.801,17 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.801,17 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.769,14 | -€32,03 |
| 9 | Chiude 50% a +€50 | +€1.446,68 | -€354,49 |
| 10 | Trailing 20% dopo +€50 | +€1.346,89 | -€454,28 |
| 11 | Take profit fisso +€75 | +€1.154,54 | -€646,63 |
| 12 | TP +€50 / SL -€50 | +€444,49 | -€1.356,67 |
| 13 | Take profit fisso +€50 | +€320,73 | -€1.480,44 |
| 14 | Take profit fisso +€25 | -€335,90 | -€2.137,07 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
