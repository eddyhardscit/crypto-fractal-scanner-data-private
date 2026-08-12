# Analisi uscite paper trading a leva

Generato: 2026-08-12T20:46:03+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4591**
- Trade con percorso cronologico utilizzabile: **4537**
- Trade che hanno raggiunto almeno +€50: **1710**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€8.373,29 | +€16.461,49 |
| 2 | TP +€50 / SL -€50 | -€17.539,86 | +€7.294,92 |
| 3 | Chiude 50% a +€50 | -€19.668,47 | +€5.166,32 |
| 4 | Protegge +€30 dopo +€50 | -€20.279,12 | +€4.555,66 |
| 5 | Protegge +€20 dopo +€50 | -€22.450,35 | +€2.384,43 |
| 6 | Strategia attuale | -€24.834,78 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.834,78 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.839,10 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€25.132,20 | -€297,42 |
| 10 | Take profit fisso +€100 | -€25.179,30 | -€344,52 |
| 11 | Pareggio dopo +€50 | -€26.337,79 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.486,55 | -€3.651,77 |
| 13 | Take profit fisso +€50 | -€33.808,64 | -€8.973,86 |
| 14 | Take profit fisso +€25 | -€36.716,59 | -€11.881,80 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
