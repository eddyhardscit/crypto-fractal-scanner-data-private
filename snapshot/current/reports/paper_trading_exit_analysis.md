# Analisi uscite paper trading a leva

Generato: 2026-07-18T18:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **204**
- Trade con percorso cronologico utilizzabile: **150**
- Trade che hanno raggiunto almeno +€50: **90**
- Di questi, chiusi poi in perdita: **16**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.955,51 | +€204,48 |
| 2 | Protegge +€20 dopo +€50 | +€1.872,82 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€1.853,28 | +€102,26 |
| 4 | Pareggio dopo +€50 | +€1.804,93 | +€53,90 |
| 5 | Strategia attuale | +€1.751,03 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.751,03 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.751,03 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.729,83 | -€21,20 |
| 9 | Chiude 50% a +€50 | +€1.451,95 | -€299,08 |
| 10 | Trailing 20% dopo +€50 | +€1.439,96 | -€311,07 |
| 11 | Take profit fisso +€75 | +€1.186,56 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€499,65 | -€1.251,38 |
| 13 | Take profit fisso +€50 | +€381,40 | -€1.369,63 |
| 14 | Take profit fisso +€25 | -€581,23 | -€2.332,26 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
