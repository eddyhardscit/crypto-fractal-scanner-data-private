# Analisi uscite paper trading a leva

Generato: 2026-07-27T20:24:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2627**
- Trade con percorso cronologico utilizzabile: **2573**
- Trade che hanno raggiunto almeno +€50: **1137**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.612,94 | +€9.632,86 |
| 2 | Protegge +€30 dopo +€50 | +€856,71 | +€876,64 |
| 3 | Chiude 50% a +€50 | +€589,19 | +€609,12 |
| 4 | Strategia attuale | -€19,92 | €0,00 |
| 5 | Take profit fisso +€200 | -€19,92 | €0,00 |
| 6 | Take profit fisso +€100 | -€22,16 | -€2,23 |
| 7 | Take profit fisso +€150 | -€24,24 | -€4,32 |
| 8 | Protegge +€20 dopo +€50 | -€61,21 | -€41,29 |
| 9 | Trailing 20% dopo +€50 | -€208,33 | -€188,41 |
| 10 | Pareggio dopo +€50 | -€814,10 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€1.783,01 | -€1.763,09 |
| 12 | Take profit fisso +€75 | -€3.725,66 | -€3.705,74 |
| 13 | Take profit fisso +€50 | -€11.277,74 | -€11.257,82 |
| 14 | Take profit fisso +€25 | -€14.502,90 | -€14.482,97 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
