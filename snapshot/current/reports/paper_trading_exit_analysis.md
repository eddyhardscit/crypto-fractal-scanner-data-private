# Analisi uscite paper trading a leva

Generato: 2026-07-20T11:23:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **364**
- Trade con percorso cronologico utilizzabile: **310**
- Trade che hanno raggiunto almeno +€50: **165**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.296,38 | +€449,20 |
| 2 | Stop loss fisso -€50 | +€2.156,00 | +€308,82 |
| 3 | Protegge +€20 dopo +€50 | +€2.105,79 | +€258,62 |
| 4 | Pareggio dopo +€50 | +€1.913,57 | +€66,40 |
| 5 | Take profit fisso +€100 | +€1.870,32 | +€23,14 |
| 6 | Strategia attuale | +€1.847,17 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.847,17 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.847,17 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.768,28 | -€78,89 |
| 10 | Trailing 20% dopo +€50 | +€1.476,00 | -€371,18 |
| 11 | Take profit fisso +€75 | +€1.018,98 | -€828,20 |
| 12 | TP +€50 / SL -€50 | +€86,58 | -€1.760,59 |
| 13 | Take profit fisso +€50 | -€238,23 | -€2.085,41 |
| 14 | Take profit fisso +€25 | -€789,95 | -€2.637,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
