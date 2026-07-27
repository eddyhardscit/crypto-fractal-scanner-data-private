# Analisi uscite paper trading a leva

Generato: 2026-07-27T06:09:29+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2112**
- Trade con percorso cronologico utilizzabile: **2058**
- Trade che hanno raggiunto almeno +€50: **934**
- Di questi, chiusi poi in perdita: **193**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.653,71 | +€8.937,89 |
| 2 | Chiude 50% a +€50 | -€867,08 | +€1.417,09 |
| 3 | Protegge +€30 dopo +€50 | -€1.460,23 | +€823,94 |
| 4 | TP +€50 / SL -€50 | -€1.878,74 | +€405,44 |
| 5 | Protegge +€20 dopo +€50 | -€1.902,99 | +€381,19 |
| 6 | Strategia attuale | -€2.284,18 | €0,00 |
| 7 | Take profit fisso +€200 | -€2.284,18 | €0,00 |
| 8 | Take profit fisso +€150 | -€2.284,91 | -€0,74 |
| 9 | Take profit fisso +€100 | -€2.343,83 | -€59,65 |
| 10 | Trailing 20% dopo +€50 | -€2.435,70 | -€151,52 |
| 11 | Pareggio dopo +€50 | -€3.127,04 | -€842,87 |
| 12 | Take profit fisso +€75 | -€5.370,52 | -€3.086,34 |
| 13 | Take profit fisso +€50 | -€10.678,49 | -€8.394,31 |
| 14 | Take profit fisso +€25 | -€14.927,03 | -€12.642,86 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
