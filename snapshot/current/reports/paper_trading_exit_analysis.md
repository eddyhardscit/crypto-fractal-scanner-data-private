# Analisi uscite paper trading a leva

Generato: 2026-08-11T23:29:49+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4174**
- Trade con percorso cronologico utilizzabile: **4120**
- Trade che hanno raggiunto almeno +€50: **1620**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€2.466,95 | +€14.507,34 |
| 2 | Chiude 50% a +€50 | -€8.214,97 | +€3.825,42 |
| 3 | TP +€50 / SL -€50 | -€8.518,54 | +€3.521,85 |
| 4 | Protegge +€30 dopo +€50 | -€9.033,07 | +€3.007,32 |
| 5 | Protegge +€20 dopo +€50 | -€10.798,50 | +€1.241,89 |
| 6 | Strategia attuale | -€12.040,39 | €0,00 |
| 7 | Take profit fisso +€200 | -€12.040,39 | €0,00 |
| 8 | Take profit fisso +€150 | -€12.044,71 | -€4,32 |
| 9 | Take profit fisso +€100 | -€12.384,91 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€12.932,99 | -€892,60 |
| 11 | Pareggio dopo +€50 | -€14.054,87 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€15.851,02 | -€3.810,63 |
| 13 | Take profit fisso +€50 | -€22.871,86 | -€10.831,47 |
| 14 | Take profit fisso +€25 | -€26.058,73 | -€14.018,34 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
