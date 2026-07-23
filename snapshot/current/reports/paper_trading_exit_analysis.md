# Analisi uscite paper trading a leva

Generato: 2026-07-23T12:38:48+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **832**
- Trade con percorso cronologico utilizzabile: **778**
- Trade che hanno raggiunto almeno +€50: **323**
- Di questi, chiusi poi in perdita: **77**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.994,89 | +€1.600,00 |
| 2 | Protegge +€30 dopo +€50 | -€4.016,82 | +€578,07 |
| 3 | Chiude 50% a +€50 | -€4.204,33 | +€390,56 |
| 4 | Protegge +€20 dopo +€50 | -€4.260,25 | +€334,63 |
| 5 | Take profit fisso +€100 | -€4.400,93 | +€193,95 |
| 6 | Pareggio dopo +€50 | -€4.515,76 | +€79,13 |
| 7 | Strategia attuale | -€4.594,89 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.594,89 | €0,00 |
| 9 | Take profit fisso +€200 | -€4.594,89 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€4.979,84 | -€384,95 |
| 11 | Take profit fisso +€75 | -€5.250,10 | -€655,22 |
| 12 | TP +€50 / SL -€50 | -€6.582,20 | -€1.987,31 |
| 13 | Take profit fisso +€25 | -€7.187,97 | -€2.593,09 |
| 14 | Take profit fisso +€50 | -€8.198,19 | -€3.603,30 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
