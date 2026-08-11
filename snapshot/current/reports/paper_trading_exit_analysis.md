# Analisi uscite paper trading a leva

Generato: 2026-08-11T02:59:22+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3674**
- Trade con percorso cronologico utilizzabile: **3620**
- Trade che hanno raggiunto almeno +€50: **1421**
- Di questi, chiusi poi in perdita: **291**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€5.265,61 | +€12.333,21 |
| 2 | Chiude 50% a +€50 | -€4.083,56 | +€2.984,03 |
| 3 | Protegge +€30 dopo +€50 | -€5.296,78 | +€1.770,81 |
| 4 | TP +€50 / SL -€50 | -€5.919,97 | +€1.147,62 |
| 5 | Protegge +€20 dopo +€50 | -€6.233,07 | +€834,52 |
| 6 | Trailing 20% dopo +€50 | -€6.913,43 | +€154,16 |
| 7 | Strategia attuale | -€7.067,60 | €0,00 |
| 8 | Take profit fisso +€200 | -€7.067,60 | €0,00 |
| 9 | Take profit fisso +€150 | -€7.071,91 | -€4,32 |
| 10 | Take profit fisso +€100 | -€7.286,31 | -€218,71 |
| 11 | Pareggio dopo +€50 | -€8.189,59 | -€1.121,99 |
| 12 | Take profit fisso +€75 | -€10.744,78 | -€3.677,18 |
| 13 | Take profit fisso +€50 | -€18.114,13 | -€11.046,53 |
| 14 | Take profit fisso +€25 | -€18.340,38 | -€11.272,78 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
