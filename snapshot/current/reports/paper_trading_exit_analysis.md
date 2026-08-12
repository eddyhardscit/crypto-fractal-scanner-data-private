# Analisi uscite paper trading a leva

Generato: 2026-08-12T01:29:11+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4181**
- Trade con percorso cronologico utilizzabile: **4127**
- Trade che hanno raggiunto almeno +€50: **1620**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€2.120,44 | +€14.511,89 |
| 2 | Chiude 50% a +€50 | -€8.566,03 | +€3.825,42 |
| 3 | TP +€50 / SL -€50 | -€8.865,05 | +€3.526,40 |
| 4 | Protegge +€30 dopo +€50 | -€9.384,13 | +€3.007,32 |
| 5 | Protegge +€20 dopo +€50 | -€11.149,56 | +€1.241,89 |
| 6 | Strategia attuale | -€12.391,45 | €0,00 |
| 7 | Take profit fisso +€200 | -€12.391,45 | €0,00 |
| 8 | Take profit fisso +€150 | -€12.395,77 | -€4,32 |
| 9 | Take profit fisso +€100 | -€12.735,97 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€13.284,05 | -€892,60 |
| 11 | Pareggio dopo +€50 | -€14.405,93 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€16.202,08 | -€3.810,63 |
| 13 | Take profit fisso +€50 | -€23.222,92 | -€10.831,47 |
| 14 | Take profit fisso +€25 | -€26.409,79 | -€14.018,34 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
