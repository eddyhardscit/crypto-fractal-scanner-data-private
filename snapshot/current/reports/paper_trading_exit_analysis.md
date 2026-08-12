# Analisi uscite paper trading a leva

Generato: 2026-08-12T14:43:13+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4496**
- Trade con percorso cronologico utilizzabile: **4442**
- Trade che hanno raggiunto almeno +€50: **1687**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€6.439,78 | +€16.286,64 |
| 2 | TP +€50 / SL -€50 | -€15.774,54 | +€6.951,88 |
| 3 | Chiude 50% a +€50 | -€17.659,74 | +€5.066,68 |
| 4 | Protegge +€30 dopo +€50 | -€18.230,76 | +€4.495,65 |
| 5 | Protegge +€20 dopo +€50 | -€20.341,99 | +€2.384,43 |
| 6 | Strategia attuale | -€22.726,42 | €0,00 |
| 7 | Take profit fisso +€200 | -€22.726,42 | €0,00 |
| 8 | Take profit fisso +€150 | -€22.730,73 | -€4,32 |
| 9 | Take profit fisso +€100 | -€23.070,93 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€23.164,34 | -€437,92 |
| 11 | Pareggio dopo +€50 | -€24.229,43 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€26.444,92 | -€3.718,50 |
| 13 | Take profit fisso +€50 | -€31.868,47 | -€9.142,05 |
| 14 | Take profit fisso +€25 | -€34.232,50 | -€11.506,08 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
