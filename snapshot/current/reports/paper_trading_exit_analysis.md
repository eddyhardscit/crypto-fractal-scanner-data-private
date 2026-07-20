# Analisi uscite paper trading a leva

Generato: 2026-07-20T14:23:36+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **383**
- Trade con percorso cronologico utilizzabile: **329**
- Trade che hanno raggiunto almeno +€50: **167**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.745,37 | +€449,20 |
| 2 | Stop loss fisso -€50 | +€1.615,67 | +€319,51 |
| 3 | Protegge +€20 dopo +€50 | +€1.554,78 | +€258,62 |
| 4 | Pareggio dopo +€50 | +€1.362,56 | +€66,40 |
| 5 | Take profit fisso +€100 | +€1.319,30 | +€23,14 |
| 6 | Strategia attuale | +€1.296,16 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.296,16 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.296,16 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.194,66 | -€101,50 |
| 10 | Trailing 20% dopo +€50 | +€924,99 | -€371,18 |
| 11 | Take profit fisso +€75 | +€472,60 | -€823,57 |
| 12 | TP +€50 / SL -€50 | -€498,96 | -€1.795,13 |
| 13 | Take profit fisso +€50 | -€834,46 | -€2.130,63 |
| 14 | Take profit fisso +€25 | -€1.302,54 | -€2.598,70 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
