# Analisi uscite paper trading a leva

Generato: 2026-07-19T18:08:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **279**
- Trade con percorso cronologico utilizzabile: **225**
- Trade che hanno raggiunto almeno +€50: **121**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.232,30 | +€338,71 |
| 2 | Protegge +€20 dopo +€50 | +€2.100,02 | +€206,43 |
| 3 | Stop loss fisso -€50 | +€2.041,95 | +€148,36 |
| 4 | Take profit fisso +€100 | +€1.983,15 | +€89,56 |
| 5 | Pareggio dopo +€50 | +€1.932,13 | +€38,54 |
| 6 | Strategia attuale | +€1.893,59 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.893,59 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.893,59 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.629,51 | -€264,08 |
| 10 | Trailing 20% dopo +€50 | +€1.461,98 | -€431,60 |
| 11 | Take profit fisso +€75 | +€1.245,26 | -€648,33 |
| 12 | TP +€50 / SL -€50 | +€325,13 | -€1.568,46 |
| 13 | Take profit fisso +€50 | +€160,77 | -€1.732,82 |
| 14 | Take profit fisso +€25 | -€696,74 | -€2.590,33 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
