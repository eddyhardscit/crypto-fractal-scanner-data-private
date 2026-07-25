# Analisi uscite paper trading a leva

Generato: 2026-07-25T18:24:19+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1491**
- Trade con percorso cronologico utilizzabile: **1437**
- Trade che hanno raggiunto almeno +€50: **718**
- Di questi, chiusi poi in perdita: **148**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.239,94 | +€4.016,78 |
| 2 | Chiude 50% a +€50 | +€4.472,58 | +€249,42 |
| 3 | Strategia attuale | +€4.223,16 | €0,00 |
| 4 | Take profit fisso +€200 | +€4.223,16 | €0,00 |
| 5 | Take profit fisso +€150 | +€4.222,42 | -€0,74 |
| 6 | Take profit fisso +€100 | +€4.186,53 | -€36,63 |
| 7 | Protegge +€20 dopo +€50 | +€4.050,42 | -€172,74 |
| 8 | Protegge +€30 dopo +€50 | +€3.884,43 | -€338,73 |
| 9 | Pareggio dopo +€50 | +€3.305,23 | -€917,93 |
| 10 | Trailing 20% dopo +€50 | +€2.370,70 | -€1.852,46 |
| 11 | Take profit fisso +€75 | +€1.693,76 | -€2.529,41 |
| 12 | TP +€50 / SL -€50 | -€441,51 | -€4.664,67 |
| 13 | Take profit fisso +€50 | -€4.320,16 | -€8.543,32 |
| 14 | Take profit fisso +€25 | -€7.130,15 | -€11.353,31 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
