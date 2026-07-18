# Analisi uscite paper trading a leva

Generato: 2026-07-18T15:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **197**
- Trade con percorso cronologico utilizzabile: **143**
- Trade che hanno raggiunto almeno +€50: **87**
- Di questi, chiusi poi in perdita: **14**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.142,69 | +€204,48 |
| 2 | Protegge +€20 dopo +€50 | +€2.060,00 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€2.031,75 | +€93,54 |
| 4 | Pareggio dopo +€50 | +€1.992,11 | +€53,90 |
| 5 | Strategia attuale | +€1.938,22 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.938,22 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.938,22 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.917,02 | -€21,20 |
| 9 | Trailing 20% dopo +€50 | +€1.627,15 | -€311,07 |
| 10 | Chiude 50% a +€50 | +€1.574,90 | -€363,32 |
| 11 | Take profit fisso +€75 | +€1.373,74 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€678,12 | -€1.260,10 |
| 13 | Take profit fisso +€50 | +€568,59 | -€1.369,63 |
| 14 | Take profit fisso +€25 | -€447,52 | -€2.385,73 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
