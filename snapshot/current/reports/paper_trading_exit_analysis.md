# Analisi uscite paper trading a leva

Generato: 2026-08-11T20:30:59+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4070**
- Trade con percorso cronologico utilizzabile: **4016**
- Trade che hanno raggiunto almeno +€50: **1587**
- Di questi, chiusi poi in perdita: **302**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€4.921,57 | +€14.122,83 |
| 2 | Chiude 50% a +€50 | -€6.094,78 | +€3.106,48 |
| 3 | TP +€50 / SL -€50 | -€6.919,91 | +€2.281,36 |
| 4 | Protegge +€30 dopo +€50 | -€6.921,46 | +€2.279,80 |
| 5 | Protegge +€20 dopo +€50 | -€8.560,39 | +€640,88 |
| 6 | Strategia attuale | -€9.201,26 | €0,00 |
| 7 | Take profit fisso +€200 | -€9.201,26 | €0,00 |
| 8 | Take profit fisso +€150 | -€9.205,58 | -€4,32 |
| 9 | Take profit fisso +€100 | -€9.545,78 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€10.706,31 | -€1.505,04 |
| 11 | Pareggio dopo +€50 | -€11.627,44 | -€2.426,18 |
| 12 | Take profit fisso +€75 | -€12.977,07 | -€3.775,81 |
| 13 | Take profit fisso +€50 | -€20.900,11 | -€11.698,85 |
| 14 | Take profit fisso +€25 | -€24.153,03 | -€14.951,76 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
