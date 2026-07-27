# Analisi uscite paper trading a leva

Generato: 2026-07-27T03:09:26+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2103**
- Trade con percorso cronologico utilizzabile: **2049**
- Trade che hanno raggiunto almeno +€50: **928**
- Di questi, chiusi poi in perdita: **193**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.329,42 | +€8.931,92 |
| 2 | Chiude 50% a +€50 | -€1.122,50 | +€1.479,99 |
| 3 | Protegge +€30 dopo +€50 | -€1.778,55 | +€823,94 |
| 4 | TP +€50 / SL -€50 | -€2.077,22 | +€525,28 |
| 5 | Protegge +€20 dopo +€50 | -€2.221,31 | +€381,19 |
| 6 | Strategia attuale | -€2.602,50 | €0,00 |
| 7 | Take profit fisso +€200 | -€2.602,50 | €0,00 |
| 8 | Take profit fisso +€150 | -€2.603,24 | -€0,74 |
| 9 | Take profit fisso +€100 | -€2.662,15 | -€59,65 |
| 10 | Trailing 20% dopo +€50 | -€2.754,02 | -€151,52 |
| 11 | Pareggio dopo +€50 | -€3.445,37 | -€842,87 |
| 12 | Take profit fisso +€75 | -€5.688,84 | -€3.086,34 |
| 13 | Take profit fisso +€50 | -€10.871,01 | -€8.268,51 |
| 14 | Take profit fisso +€25 | -€14.996,07 | -€12.393,57 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
