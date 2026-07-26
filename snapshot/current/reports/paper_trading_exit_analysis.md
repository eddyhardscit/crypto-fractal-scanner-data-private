# Analisi uscite paper trading a leva

Generato: 2026-07-26T13:54:19+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1925**
- Trade con percorso cronologico utilizzabile: **1871**
- Trade che hanno raggiunto almeno +€50: **885**
- Di questi, chiusi poi in perdita: **184**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.158,46 | +€8.789,97 |
| 2 | Chiude 50% a +€50 | +€1.250,11 | +€881,62 |
| 3 | Protegge +€30 dopo +€50 | +€828,48 | +€459,99 |
| 4 | Protegge +€20 dopo +€50 | +€581,36 | +€212,88 |
| 5 | Strategia attuale | +€368,49 | €0,00 |
| 6 | Take profit fisso +€200 | +€368,49 | €0,00 |
| 7 | Take profit fisso +€150 | +€367,75 | -€0,74 |
| 8 | Take profit fisso +€100 | +€303,78 | -€64,70 |
| 9 | TP +€50 / SL -€50 | +€110,85 | -€257,63 |
| 10 | Trailing 20% dopo +€50 | -€353,47 | -€721,96 |
| 11 | Pareggio dopo +€50 | -€487,78 | -€856,27 |
| 12 | Take profit fisso +€75 | -€2.732,59 | -€3.101,08 |
| 13 | Take profit fisso +€50 | -€8.540,99 | -€8.909,48 |
| 14 | Take profit fisso +€25 | -€13.234,84 | -€13.603,32 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
