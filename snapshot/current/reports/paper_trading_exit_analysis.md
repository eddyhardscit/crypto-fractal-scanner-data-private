# Analisi uscite paper trading a leva

Generato: 2026-08-12T05:28:11+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4252**
- Trade con percorso cronologico utilizzabile: **4198**
- Trade che hanno raggiunto almeno +€50: **1634**
- Di questi, chiusi poi in perdita: **311**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€510,18 | +€14.567,48 |
| 2 | Chiude 50% a +€50 | -€10.405,89 | +€3.651,41 |
| 3 | TP +€50 / SL -€50 | -€10.823,34 | +€3.233,96 |
| 4 | Protegge +€30 dopo +€50 | -€11.049,98 | +€3.007,32 |
| 5 | Protegge +€20 dopo +€50 | -€12.815,41 | +€1.241,89 |
| 6 | Strategia attuale | -€14.057,30 | €0,00 |
| 7 | Take profit fisso +€200 | -€14.057,30 | €0,00 |
| 8 | Take profit fisso +€150 | -€14.061,61 | -€4,32 |
| 9 | Take profit fisso +€100 | -€14.401,81 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€15.434,23 | -€1.376,93 |
| 11 | Pareggio dopo +€50 | -€16.071,78 | -€2.014,48 |
| 12 | Take profit fisso +€75 | -€17.880,68 | -€3.823,39 |
| 13 | Take profit fisso +€50 | -€25.236,80 | -€11.179,50 |
| 14 | Take profit fisso +€25 | -€28.738,78 | -€14.681,48 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
