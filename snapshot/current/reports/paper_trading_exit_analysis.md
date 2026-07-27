# Analisi uscite paper trading a leva

Generato: 2026-07-27T01:09:24+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2050**
- Trade con percorso cronologico utilizzabile: **1996**
- Trade che hanno raggiunto almeno +€50: **922**
- Di questi, chiusi poi in perdita: **188**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€7.801,39 | +€8.881,42 |
| 2 | Chiude 50% a +€50 | +€251,98 | +€1.332,01 |
| 3 | Protegge +€30 dopo +€50 | -€278,37 | +€801,67 |
| 4 | TP +€50 / SL -€50 | -€647,53 | +€432,50 |
| 5 | Protegge +€20 dopo +€50 | -€711,12 | +€368,91 |
| 6 | Strategia attuale | -€1.080,03 | €0,00 |
| 7 | Take profit fisso +€200 | -€1.080,03 | €0,00 |
| 8 | Take profit fisso +€150 | -€1.080,77 | -€0,74 |
| 9 | Take profit fisso +€100 | -€1.139,69 | -€59,65 |
| 10 | Trailing 20% dopo +€50 | -€1.258,88 | -€178,85 |
| 11 | Pareggio dopo +€50 | -€1.922,90 | -€842,87 |
| 12 | Take profit fisso +€75 | -€4.166,37 | -€3.086,34 |
| 13 | Take profit fisso +€50 | -€9.390,82 | -€8.310,79 |
| 14 | Take profit fisso +€25 | -€13.646,23 | -€12.566,20 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
