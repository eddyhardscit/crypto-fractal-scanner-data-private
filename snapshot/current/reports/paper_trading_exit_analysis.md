# Analisi uscite paper trading a leva

Generato: 2026-07-18T19:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **209**
- Trade con percorso cronologico utilizzabile: **155**
- Trade che hanno raggiunto almeno +€50: **91**
- Di questi, chiusi poi in perdita: **16**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.927,78 | +€204,48 |
| 2 | Protegge +€20 dopo +€50 | +€1.845,09 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€1.826,49 | +€103,18 |
| 4 | Pareggio dopo +€50 | +€1.777,20 | +€53,90 |
| 5 | Strategia attuale | +€1.723,30 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.723,30 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.723,30 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.702,11 | -€21,20 |
| 9 | Trailing 20% dopo +€50 | +€1.412,24 | -€311,07 |
| 10 | Chiude 50% a +€50 | +€1.412,23 | -€311,07 |
| 11 | Take profit fisso +€75 | +€1.158,83 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€448,87 | -€1.274,43 |
| 13 | Take profit fisso +€50 | +€329,70 | -€1.393,61 |
| 14 | Take profit fisso +€25 | -€657,94 | -€2.381,24 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
