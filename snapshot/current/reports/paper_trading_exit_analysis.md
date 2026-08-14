# Analisi uscite paper trading a leva

Generato: 2026-08-14T11:13:38+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4992**
- Trade con percorso cronologico utilizzabile: **4938**
- Trade che hanno raggiunto almeno +€50: **1888**
- Di questi, chiusi poi in perdita: **362**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.609,25 | +€19.046,04 |
| 2 | TP +€50 / SL -€50 | -€16.014,06 | +€5.641,23 |
| 3 | Protegge +€30 dopo +€50 | -€16.677,84 | +€4.977,45 |
| 4 | Chiude 50% a +€50 | -€18.086,91 | +€3.568,38 |
| 5 | Protegge +€20 dopo +€50 | -€19.095,02 | +€2.560,27 |
| 6 | Strategia attuale | -€21.655,29 | €0,00 |
| 7 | Take profit fisso +€200 | -€21.655,29 | €0,00 |
| 8 | Take profit fisso +€150 | -€21.659,60 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€22.043,63 | -€388,34 |
| 10 | Take profit fisso +€100 | -€22.284,57 | -€629,28 |
| 11 | Pareggio dopo +€50 | -€23.054,32 | -€1.399,03 |
| 12 | Take profit fisso +€75 | -€27.417,32 | -€5.762,03 |
| 13 | Take profit fisso +€50 | -€34.867,38 | -€13.212,09 |
| 14 | Take profit fisso +€25 | -€40.674,99 | -€19.019,70 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
