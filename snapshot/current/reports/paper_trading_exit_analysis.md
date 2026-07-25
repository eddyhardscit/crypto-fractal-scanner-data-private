# Analisi uscite paper trading a leva

Generato: 2026-07-25T13:24:01+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1363**
- Trade con percorso cronologico utilizzabile: **1309**
- Trade che hanno raggiunto almeno +€50: **654**
- Di questi, chiusi poi in perdita: **144**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.816,01 | +€3.129,43 |
| 2 | Chiude 50% a +€50 | +€3.523,20 | +€836,62 |
| 3 | Take profit fisso +€100 | +€2.929,09 | +€242,51 |
| 4 | Strategia attuale | +€2.686,58 | €0,00 |
| 5 | Take profit fisso +€150 | +€2.686,58 | €0,00 |
| 6 | Take profit fisso +€200 | +€2.686,58 | €0,00 |
| 7 | Protegge +€20 dopo +€50 | +€2.263,11 | -€423,47 |
| 8 | Protegge +€30 dopo +€50 | +€2.167,45 | -€519,13 |
| 9 | Pareggio dopo +€50 | +€1.567,45 | -€1.119,13 |
| 10 | Take profit fisso +€75 | +€1.304,59 | -€1.381,99 |
| 11 | Trailing 20% dopo +€50 | +€876,75 | -€1.809,83 |
| 12 | TP +€50 / SL -€50 | -€956,13 | -€3.642,71 |
| 13 | Take profit fisso +€50 | -€4.098,63 | -€6.785,21 |
| 14 | Take profit fisso +€25 | -€6.186,68 | -€8.873,26 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
