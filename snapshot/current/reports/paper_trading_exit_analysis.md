# Analisi uscite paper trading a leva

Generato: 2026-07-23T22:38:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **967**
- Trade con percorso cronologico utilizzabile: **913**
- Trade che hanno raggiunto almeno +€50: **400**
- Di questi, chiusi poi in perdita: **88**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€624,16 | +€2.028,40 |
| 2 | Take profit fisso +€100 | -€2.550,71 | +€101,85 |
| 3 | Chiude 50% a +€50 | -€2.606,84 | +€45,72 |
| 4 | Strategia attuale | -€2.652,56 | €0,00 |
| 5 | Take profit fisso +€150 | -€2.652,56 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.652,56 | €0,00 |
| 7 | Protegge +€20 dopo +€50 | -€2.995,63 | -€343,07 |
| 8 | Protegge +€30 dopo +€50 | -€3.032,74 | -€380,18 |
| 9 | Take profit fisso +€75 | -€3.551,96 | -€899,40 |
| 10 | Pareggio dopo +€50 | -€3.570,27 | -€917,70 |
| 11 | Trailing 20% dopo +€50 | -€4.252,76 | -€1.600,20 |
| 12 | TP +€50 / SL -€50 | -€5.519,79 | -€2.867,23 |
| 13 | Take profit fisso +€25 | -€7.221,70 | -€4.569,13 |
| 14 | Take profit fisso +€50 | -€7.564,18 | -€4.911,62 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
