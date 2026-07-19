# Analisi uscite paper trading a leva

Generato: 2026-07-19T14:53:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **269**
- Trade con percorso cronologico utilizzabile: **215**
- Trade che hanno raggiunto almeno +€50: **116**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.981,47 | +€327,00 |
| 2 | Protegge +€20 dopo +€50 | +€1.859,19 | +€204,73 |
| 3 | Stop loss fisso -€50 | +€1.794,70 | +€140,24 |
| 4 | Take profit fisso +€100 | +€1.754,25 | +€99,78 |
| 5 | Pareggio dopo +€50 | +€1.711,30 | +€56,83 |
| 6 | Strategia attuale | +€1.654,47 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.654,47 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.654,47 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.465,19 | -€189,27 |
| 10 | Trailing 20% dopo +€50 | +€1.258,36 | -€396,11 |
| 11 | Take profit fisso +€75 | +€1.088,68 | -€565,79 |
| 12 | TP +€50 / SL -€50 | +€227,48 | -€1.426,98 |
| 13 | Take profit fisso +€50 | +€71,26 | -€1.583,21 |
| 14 | Take profit fisso +€25 | -€661,26 | -€2.315,73 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
