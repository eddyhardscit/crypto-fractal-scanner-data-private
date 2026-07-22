# Analisi uscite paper trading a leva

Generato: 2026-07-22T07:08:46+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **691**
- Trade con percorso cronologico utilizzabile: **637**
- Trade che hanno raggiunto almeno +€50: **278**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.123,39 | +€1.221,99 |
| 2 | Protegge +€30 dopo +€50 | -€1.817,83 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€2.015,17 | +€330,22 |
| 4 | Take profit fisso +€100 | -€2.164,51 | +€180,88 |
| 5 | Chiude 50% a +€50 | -€2.239,85 | +€105,54 |
| 6 | Pareggio dopo +€50 | -€2.277,78 | +€67,61 |
| 7 | Strategia attuale | -€2.345,39 | €0,00 |
| 8 | Take profit fisso +€150 | -€2.345,39 | €0,00 |
| 9 | Take profit fisso +€200 | -€2.345,39 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€2.822,98 | -€477,59 |
| 11 | Take profit fisso +€75 | -€2.899,25 | -€553,86 |
| 12 | TP +€50 / SL -€50 | -€4.365,23 | -€2.019,84 |
| 13 | Take profit fisso +€25 | -€5.016,71 | -€2.671,32 |
| 14 | Take profit fisso +€50 | -€5.603,22 | -€3.257,83 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
