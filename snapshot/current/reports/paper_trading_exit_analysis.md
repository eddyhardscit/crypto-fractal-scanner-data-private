# Analisi uscite paper trading a leva

Generato: 2026-07-26T23:09:24+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2012**
- Trade con percorso cronologico utilizzabile: **1958**
- Trade che hanno raggiunto almeno +€50: **907**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.509,04 | +€8.871,15 |
| 2 | Chiude 50% a +€50 | +€708,69 | +€1.070,79 |
| 3 | Protegge +€30 dopo +€50 | +€243,07 | +€605,18 |
| 4 | Protegge +€20 dopo +€50 | -€54,04 | +€308,07 |
| 5 | Strategia attuale | -€362,11 | €0,00 |
| 6 | Take profit fisso +€200 | -€362,11 | €0,00 |
| 7 | Take profit fisso +€150 | -€362,84 | -€0,74 |
| 8 | TP +€50 / SL -€50 | -€416,36 | -€54,26 |
| 9 | Take profit fisso +€100 | -€421,76 | -€59,65 |
| 10 | Trailing 20% dopo +€50 | -€923,12 | -€561,02 |
| 11 | Pareggio dopo +€50 | -€1.204,97 | -€842,87 |
| 12 | Take profit fisso +€75 | -€3.448,45 | -€3.086,34 |
| 13 | Take profit fisso +€50 | -€9.149,38 | -€8.787,28 |
| 14 | Take profit fisso +€25 | -€13.586,11 | -€13.224,00 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
