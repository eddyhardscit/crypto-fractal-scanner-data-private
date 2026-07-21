# Analisi uscite paper trading a leva

Generato: 2026-07-21T22:53:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **603**
- Trade con percorso cronologico utilizzabile: **549**
- Trade che hanno raggiunto almeno +€50: **256**
- Di questi, chiusi poi in perdita: **62**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€361,16 | +€946,46 |
| 2 | Protegge +€30 dopo +€50 | +€5,50 | +€590,80 |
| 3 | Protegge +€20 dopo +€50 | -€255,09 | +€330,22 |
| 4 | Chiude 50% a +€50 | -€310,64 | +€274,66 |
| 5 | Take profit fisso +€100 | -€398,93 | +€186,37 |
| 6 | Pareggio dopo +€50 | -€517,69 | +€67,61 |
| 7 | Strategia attuale | -€585,30 | €0,00 |
| 8 | Take profit fisso +€150 | -€585,30 | €0,00 |
| 9 | Take profit fisso +€200 | -€585,30 | €0,00 |
| 10 | Take profit fisso +€75 | -€983,75 | -€398,44 |
| 11 | Trailing 20% dopo +€50 | -€991,13 | -€405,82 |
| 12 | TP +€50 / SL -€50 | -€2.347,26 | -€1.761,95 |
| 13 | Take profit fisso +€50 | -€3.309,71 | -€2.724,41 |
| 14 | Take profit fisso +€25 | -€3.610,03 | -€3.024,72 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
