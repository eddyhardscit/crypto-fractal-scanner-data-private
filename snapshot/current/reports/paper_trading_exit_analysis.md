# Analisi uscite paper trading a leva

Generato: 2026-08-13T21:14:38+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4821**
- Trade con percorso cronologico utilizzabile: **4767**
- Trade che hanno raggiunto almeno +€50: **1806**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.852,98 | +€18.376,74 |
| 2 | TP +€50 / SL -€50 | -€17.444,33 | +€5.785,39 |
| 3 | Protegge +€30 dopo +€50 | -€18.719,13 | +€4.510,59 |
| 4 | Chiude 50% a +€50 | -€19.739,30 | +€3.490,42 |
| 5 | Protegge +€20 dopo +€50 | -€20.950,37 | +€2.279,36 |
| 6 | Strategia attuale | -€23.229,72 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.229,72 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.234,04 | -€4,32 |
| 9 | Take profit fisso +€100 | -€23.784,50 | -€554,78 |
| 10 | Trailing 20% dopo +€50 | -€23.934,72 | -€705,00 |
| 11 | Pareggio dopo +€50 | -€24.732,73 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.315,31 | -€5.085,58 |
| 13 | Take profit fisso +€50 | -€35.628,36 | -€12.398,64 |
| 14 | Take profit fisso +€25 | -€40.867,52 | -€17.637,80 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
