# Analisi uscite paper trading a leva

Generato: 2026-07-21T23:53:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **608**
- Trade con percorso cronologico utilizzabile: **554**
- Trade che hanno raggiunto almeno +€50: **256**
- Di questi, chiusi poi in perdita: **62**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€111,16 | +€967,79 |
| 2 | Protegge +€30 dopo +€50 | -€265,83 | +€590,80 |
| 3 | Protegge +€20 dopo +€50 | -€526,41 | +€330,22 |
| 4 | Chiude 50% a +€50 | -€581,97 | +€274,66 |
| 5 | Take profit fisso +€100 | -€670,26 | +€186,37 |
| 6 | Pareggio dopo +€50 | -€789,02 | +€67,61 |
| 7 | Strategia attuale | -€856,63 | €0,00 |
| 8 | Take profit fisso +€150 | -€856,63 | €0,00 |
| 9 | Take profit fisso +€200 | -€856,63 | €0,00 |
| 10 | Take profit fisso +€75 | -€1.255,07 | -€398,44 |
| 11 | Trailing 20% dopo +€50 | -€1.262,45 | -€405,82 |
| 12 | TP +€50 / SL -€50 | -€2.597,26 | -€1.740,63 |
| 13 | Take profit fisso +€25 | -€3.563,00 | -€2.706,37 |
| 14 | Take profit fisso +€50 | -€3.581,04 | -€2.724,41 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
