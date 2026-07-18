# Analisi uscite paper trading a leva

Generato: 2026-07-18T20:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **212**
- Trade con percorso cronologico utilizzabile: **158**
- Trade che hanno raggiunto almeno +€50: **91**
- Di questi, chiusi poi in perdita: **16**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.825,74 | +€204,48 |
| 2 | Protegge +€20 dopo +€50 | +€1.743,05 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€1.726,40 | +€105,14 |
| 4 | Pareggio dopo +€50 | +€1.675,16 | +€53,90 |
| 5 | Strategia attuale | +€1.621,26 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.621,26 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.621,26 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.600,07 | -€21,20 |
| 9 | Trailing 20% dopo +€50 | +€1.310,19 | -€311,07 |
| 10 | Chiude 50% a +€50 | +€1.310,19 | -€311,07 |
| 11 | Take profit fisso +€75 | +€1.056,79 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€348,79 | -€1.272,47 |
| 13 | Take profit fisso +€50 | +€227,65 | -€1.393,61 |
| 14 | Take profit fisso +€25 | -€582,94 | -€2.204,20 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
