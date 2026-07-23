# Analisi uscite paper trading a leva

Generato: 2026-07-23T02:23:50+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **824**
- Trade con percorso cronologico utilizzabile: **770**
- Trade che hanno raggiunto almeno +€50: **323**
- Di questi, chiusi poi in perdita: **77**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.850,60 | +€1.583,93 |
| 2 | Protegge +€30 dopo +€50 | -€3.856,46 | +€578,07 |
| 3 | Chiude 50% a +€50 | -€4.043,97 | +€390,56 |
| 4 | Protegge +€20 dopo +€50 | -€4.099,89 | +€334,63 |
| 5 | Take profit fisso +€100 | -€4.240,57 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€4.355,40 | +€79,13 |
| 7 | Strategia attuale | -€4.434,53 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.434,53 | €0,00 |
| 9 | Take profit fisso +€200 | -€4.434,53 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.819,48 | -€384,95 |
| 11 | Take profit fisso +€75 | -€5.089,74 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€6.437,90 | -€2.003,38 |
| 13 | Take profit fisso +€25 | -€7.027,61 | -€2.593,09 |
| 14 | Take profit fisso +€50 | -€8.037,83 | -€3.603,30 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
