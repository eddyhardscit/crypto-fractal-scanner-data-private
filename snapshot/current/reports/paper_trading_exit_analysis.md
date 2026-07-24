# Analisi uscite paper trading a leva

Generato: 2026-07-24T02:53:55+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1048**
- Trade con percorso cronologico utilizzabile: **994**
- Trade che hanno raggiunto almeno +€50: **456**
- Di questi, chiusi poi in perdita: **97**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€191,35 | +€2.275,06 |
| 2 | Chiude 50% a +€50 | -€1.579,16 | +€504,55 |
| 3 | Take profit fisso +€100 | -€1.993,47 | +€90,24 |
| 4 | Strategia attuale | -€2.083,72 | €0,00 |
| 5 | Take profit fisso +€150 | -€2.083,72 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.083,72 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€2.109,67 | -€25,95 |
| 8 | Protegge +€20 dopo +€50 | -€2.265,64 | -€181,92 |
| 9 | Take profit fisso +€75 | -€2.899,32 | -€815,61 |
| 10 | Pareggio dopo +€50 | -€2.989,10 | -€905,38 |
| 11 | Trailing 20% dopo +€50 | -€3.076,39 | -€992,68 |
| 12 | TP +€50 / SL -€50 | -€4.354,62 | -€2.270,90 |
| 13 | Take profit fisso +€50 | -€6.645,67 | -€4.561,96 |
| 14 | Take profit fisso +€25 | -€7.005,35 | -€4.921,63 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
