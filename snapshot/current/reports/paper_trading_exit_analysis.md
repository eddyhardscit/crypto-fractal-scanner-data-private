# Analisi uscite paper trading a leva

Generato: 2026-07-20T06:08:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **321**
- Trade con percorso cronologico utilizzabile: **267**
- Trade che hanno raggiunto almeno +€50: **140**
- Di questi, chiusi poi in perdita: **33**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.916,20 | +€287,52 |
| 2 | Stop loss fisso -€50 | +€1.864,26 | +€235,58 |
| 3 | Protegge +€20 dopo +€50 | +€1.795,62 | +€166,93 |
| 4 | Take profit fisso +€100 | +€1.701,08 | +€72,39 |
| 5 | Pareggio dopo +€50 | +€1.684,75 | +€56,07 |
| 6 | Strategia attuale | +€1.628,68 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.628,68 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.628,68 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.447,49 | -€181,20 |
| 10 | Trailing 20% dopo +€50 | +€1.022,51 | -€606,17 |
| 11 | Take profit fisso +€75 | +€843,61 | -€785,07 |
| 12 | TP +€50 / SL -€50 | -€98,90 | -€1.727,58 |
| 13 | Take profit fisso +€50 | -€350,47 | -€1.979,15 |
| 14 | Take profit fisso +€25 | -€770,59 | -€2.399,28 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
