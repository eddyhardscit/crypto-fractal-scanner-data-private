# Analisi uscite paper trading a leva

Generato: 2026-08-12T00:30:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4175**
- Trade con percorso cronologico utilizzabile: **4121**
- Trade che hanno raggiunto almeno +€50: **1620**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€2.416,95 | +€14.507,77 |
| 2 | Chiude 50% a +€50 | -€8.265,39 | +€3.825,42 |
| 3 | TP +€50 / SL -€50 | -€8.568,54 | +€3.522,28 |
| 4 | Protegge +€30 dopo +€50 | -€9.083,50 | +€3.007,32 |
| 5 | Protegge +€20 dopo +€50 | -€10.848,93 | +€1.241,89 |
| 6 | Strategia attuale | -€12.090,82 | €0,00 |
| 7 | Take profit fisso +€200 | -€12.090,82 | €0,00 |
| 8 | Take profit fisso +€150 | -€12.095,14 | -€4,32 |
| 9 | Take profit fisso +€100 | -€12.435,34 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€12.983,42 | -€892,60 |
| 11 | Pareggio dopo +€50 | -€14.105,30 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€15.901,45 | -€3.810,63 |
| 13 | Take profit fisso +€50 | -€22.922,29 | -€10.831,47 |
| 14 | Take profit fisso +€25 | -€26.109,16 | -€14.018,34 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
