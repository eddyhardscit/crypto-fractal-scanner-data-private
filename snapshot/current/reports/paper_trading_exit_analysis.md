# Analisi uscite paper trading a leva

Generato: 2026-07-19T22:08:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **287**
- Trade con percorso cronologico utilizzabile: **233**
- Trade che hanno raggiunto almeno +€50: **124**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.259,99 | +€338,71 |
| 2 | Protegge +€20 dopo +€50 | +€2.127,72 | +€206,43 |
| 3 | Stop loss fisso -€50 | +€2.084,02 | +€162,73 |
| 4 | Take profit fisso +€100 | +€2.009,79 | +€88,50 |
| 5 | Pareggio dopo +€50 | +€1.959,83 | +€38,54 |
| 6 | Strategia attuale | +€1.921,29 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.921,29 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.921,29 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.609,11 | -€312,18 |
| 10 | Trailing 20% dopo +€50 | +€1.489,68 | -€431,60 |
| 11 | Take profit fisso +€75 | +€1.246,90 | -€674,39 |
| 12 | TP +€50 / SL -€50 | +€270,99 | -€1.650,29 |
| 13 | Take profit fisso +€50 | +€92,27 | -€1.829,02 |
| 14 | Take profit fisso +€25 | -€655,77 | -€2.577,06 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
