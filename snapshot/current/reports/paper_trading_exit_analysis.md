# Analisi uscite paper trading a leva

Generato: 2026-08-14T01:12:09+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4842**
- Trade con percorso cronologico utilizzabile: **4788**
- Trade che hanno raggiunto almeno +€50: **1810**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€4.840,98 | +€18.393,41 |
| 2 | TP +€50 / SL -€50 | -€17.372,23 | +€5.862,16 |
| 3 | Protegge +€30 dopo +€50 | -€18.723,80 | +€4.510,59 |
| 4 | Chiude 50% a +€50 | -€19.713,92 | +€3.520,47 |
| 5 | Protegge +€20 dopo +€50 | -€20.955,03 | +€2.279,36 |
| 6 | Strategia attuale | -€23.234,39 | €0,00 |
| 7 | Take profit fisso +€200 | -€23.234,39 | €0,00 |
| 8 | Take profit fisso +€150 | -€23.238,71 | -€4,32 |
| 9 | Take profit fisso +€100 | -€23.789,17 | -€554,78 |
| 10 | Trailing 20% dopo +€50 | -€23.910,73 | -€676,34 |
| 11 | Pareggio dopo +€50 | -€24.737,40 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.319,97 | -€5.085,58 |
| 13 | Take profit fisso +€50 | -€35.572,94 | -€12.338,55 |
| 14 | Take profit fisso +€25 | -€40.882,54 | -€17.648,15 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
