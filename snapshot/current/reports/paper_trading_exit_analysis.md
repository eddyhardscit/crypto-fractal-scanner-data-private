# Analisi uscite paper trading a leva

Generato: 2026-07-20T15:23:38+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **389**
- Trade con percorso cronologico utilizzabile: **335**
- Trade che hanno raggiunto almeno +€50: **167**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.471,26 | +€449,20 |
| 2 | Stop loss fisso -€50 | +€1.362,54 | +€340,47 |
| 3 | Protegge +€20 dopo +€50 | +€1.280,68 | +€258,62 |
| 4 | Pareggio dopo +€50 | +€1.088,46 | +€66,40 |
| 5 | Take profit fisso +€100 | +€1.045,20 | +€23,14 |
| 6 | Strategia attuale | +€1.022,06 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.022,06 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.022,06 | €0,00 |
| 9 | Chiude 50% a +€50 | +€920,56 | -€101,50 |
| 10 | Trailing 20% dopo +€50 | +€650,89 | -€371,18 |
| 11 | Take profit fisso +€75 | +€198,50 | -€823,57 |
| 12 | TP +€50 / SL -€50 | -€752,10 | -€1.774,16 |
| 13 | Take profit fisso +€50 | -€1.108,57 | -€2.130,63 |
| 14 | Take profit fisso +€25 | -€1.576,64 | -€2.598,70 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
