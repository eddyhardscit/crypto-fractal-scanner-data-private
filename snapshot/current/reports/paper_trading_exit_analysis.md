# Analisi uscite paper trading a leva

Generato: 2026-08-12T06:28:50+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4300**
- Trade con percorso cronologico utilizzabile: **4246**
- Trade che hanno raggiunto almeno +€50: **1634**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€939,05 | +€15.514,31 |
| 2 | TP +€50 / SL -€50 | -€12.272,57 | +€4.180,79 |
| 3 | Chiude 50% a +€50 | -€12.801,95 | +€3.651,41 |
| 4 | Protegge +€30 dopo +€50 | -€13.446,04 | +€3.007,32 |
| 5 | Protegge +€20 dopo +€50 | -€15.211,47 | +€1.241,89 |
| 6 | Strategia attuale | -€16.453,36 | €0,00 |
| 7 | Take profit fisso +€200 | -€16.453,36 | €0,00 |
| 8 | Take profit fisso +€150 | -€16.457,68 | -€4,32 |
| 9 | Take profit fisso +€100 | -€16.797,88 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€17.830,29 | -€1.376,93 |
| 11 | Pareggio dopo +€50 | -€18.467,84 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€20.276,75 | -€3.823,39 |
| 13 | Take profit fisso +€50 | -€27.632,86 | -€11.179,50 |
| 14 | Take profit fisso +€25 | -€29.827,65 | -€13.374,29 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
