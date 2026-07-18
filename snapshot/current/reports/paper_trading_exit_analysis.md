# Analisi uscite paper trading a leva

Generato: 2026-07-18T23:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **218**
- Trade con percorso cronologico utilizzabile: **164**
- Trade che hanno raggiunto almeno +€50: **92**
- Di questi, chiusi poi in perdita: **16**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.699,57 | +€204,06 |
| 2 | Protegge +€20 dopo +€50 | +€1.617,29 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€1.603,27 | +€107,77 |
| 4 | Pareggio dopo +€50 | +€1.549,40 | +€53,90 |
| 5 | Strategia attuale | +€1.495,51 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.495,51 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.495,51 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.474,31 | -€21,20 |
| 9 | Chiude 50% a +€50 | +€1.194,22 | -€301,28 |
| 10 | Trailing 20% dopo +€50 | +€1.183,12 | -€312,38 |
| 11 | Take profit fisso +€75 | +€931,03 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€245,24 | -€1.250,26 |
| 13 | Take profit fisso +€50 | +€121,48 | -€1.374,03 |
| 14 | Take profit fisso +€25 | -€460,90 | -€1.956,41 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
