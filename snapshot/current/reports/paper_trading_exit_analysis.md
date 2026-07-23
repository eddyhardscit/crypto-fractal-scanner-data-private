# Analisi uscite paper trading a leva

Generato: 2026-07-23T13:38:49+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **848**
- Trade con percorso cronologico utilizzabile: **794**
- Trade che hanno raggiunto almeno +€50: **328**
- Di questi, chiusi poi in perdita: **81**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€3.601,38 | +€1.664,36 |
| 2 | Protegge +€30 dopo +€50 | -€4.687,67 | +€578,07 |
| 3 | Chiude 50% a +€50 | -€4.715,13 | +€550,61 |
| 4 | Protegge +€20 dopo +€50 | -€4.931,10 | +€334,63 |
| 5 | Take profit fisso +€100 | -€5.071,78 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€5.186,60 | +€79,13 |
| 7 | Strategia attuale | -€5.265,73 | €0,00 |
| 8 | Take profit fisso +€150 | -€5.265,73 | €0,00 |
| 9 | Take profit fisso +€200 | -€5.265,73 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€5.650,68 | -€384,95 |
| 11 | Take profit fisso +€75 | -€5.940,68 | -€674,94 |
| 12 | TP +€50 / SL -€50 | -€7.233,41 | -€1.967,67 |
| 13 | Take profit fisso +€25 | -€7.264,53 | -€1.998,79 |
| 14 | Take profit fisso +€50 | -€8.913,76 | -€3.648,03 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
