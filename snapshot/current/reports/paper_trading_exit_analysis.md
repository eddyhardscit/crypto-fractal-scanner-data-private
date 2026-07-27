# Analisi uscite paper trading a leva

Generato: 2026-07-27T00:09:22+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2013**
- Trade con percorso cronologico utilizzabile: **1959**
- Trade che hanno raggiunto almeno +€50: **907**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.510,00 | +€8.871,15 |
| 2 | Chiude 50% a +€50 | +€709,65 | +€1.070,79 |
| 3 | Protegge +€30 dopo +€50 | +€244,03 | +€605,18 |
| 4 | Protegge +€20 dopo +€50 | -€53,08 | +€308,07 |
| 5 | Strategia attuale | -€361,15 | €0,00 |
| 6 | Take profit fisso +€200 | -€361,15 | €0,00 |
| 7 | Take profit fisso +€150 | -€361,88 | -€0,74 |
| 8 | TP +€50 / SL -€50 | -€415,40 | -€54,26 |
| 9 | Take profit fisso +€100 | -€420,80 | -€59,65 |
| 10 | Trailing 20% dopo +€50 | -€922,16 | -€561,02 |
| 11 | Pareggio dopo +€50 | -€1.204,01 | -€842,87 |
| 12 | Take profit fisso +€75 | -€3.447,49 | -€3.086,34 |
| 13 | Take profit fisso +€50 | -€9.148,42 | -€8.787,28 |
| 14 | Take profit fisso +€25 | -€13.585,15 | -€13.224,00 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
