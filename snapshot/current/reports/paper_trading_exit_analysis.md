# Analisi uscite paper trading a leva

Generato: 2026-07-20T12:23:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **373**
- Trade con percorso cronologico utilizzabile: **319**
- Trade che hanno raggiunto almeno +€50: **167**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.054,06 | +€449,20 |
| 2 | Stop loss fisso -€50 | +€1.951,22 | +€346,35 |
| 3 | Protegge +€20 dopo +€50 | +€1.863,48 | +€258,62 |
| 4 | Pareggio dopo +€50 | +€1.671,26 | +€66,40 |
| 5 | Take profit fisso +€100 | +€1.628,00 | +€23,14 |
| 6 | Strategia attuale | +€1.604,86 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.604,86 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.604,86 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.503,36 | -€101,50 |
| 10 | Trailing 20% dopo +€50 | +€1.233,69 | -€371,18 |
| 11 | Take profit fisso +€75 | +€781,30 | -€823,57 |
| 12 | TP +€50 / SL -€50 | -€163,42 | -€1.768,28 |
| 13 | Take profit fisso +€50 | -€525,77 | -€2.130,63 |
| 14 | Take profit fisso +€25 | -€1.049,35 | -€2.654,21 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
