# Analisi uscite paper trading a leva

Generato: 2026-07-20T09:23:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **350**
- Trade con percorso cronologico utilizzabile: **296**
- Trade che hanno raggiunto almeno +€50: **155**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.583,25 | +€433,98 |
| 2 | Stop loss fisso -€50 | +€1.435,86 | +€286,59 |
| 3 | Protegge +€20 dopo +€50 | +€1.402,66 | +€253,39 |
| 4 | Chiude 50% a +€50 | +€1.255,93 | +€106,65 |
| 5 | Take profit fisso +€100 | +€1.221,67 | +€72,39 |
| 6 | Pareggio dopo +€50 | +€1.215,67 | +€66,40 |
| 7 | Strategia attuale | +€1.149,27 | €0,00 |
| 8 | Take profit fisso +€150 | +€1.149,27 | €0,00 |
| 9 | Take profit fisso +€200 | +€1.149,27 | €0,00 |
| 10 | Trailing 20% dopo +€50 | +€754,84 | -€394,44 |
| 11 | Take profit fisso +€75 | +€545,33 | -€603,94 |
| 12 | TP +€50 / SL -€50 | -€245,58 | -€1.394,86 |
| 13 | Take profit fisso +€50 | -€548,16 | -€1.697,44 |
| 14 | Take profit fisso +€25 | -€892,72 | -€2.041,99 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
