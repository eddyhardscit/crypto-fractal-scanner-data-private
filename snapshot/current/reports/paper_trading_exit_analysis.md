# Analisi uscite paper trading a leva

Generato: 2026-07-22T06:08:46+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **673**
- Trade con percorso cronologico utilizzabile: **619**
- Trade che hanno raggiunto almeno +€50: **271**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.233,57 | +€1.170,13 |
| 2 | Protegge +€30 dopo +€50 | -€1.812,90 | +€590,80 |
| 3 | Protegge +€20 dopo +€50 | -€2.073,49 | +€330,22 |
| 4 | Chiude 50% a +€50 | -€2.143,07 | +€260,63 |
| 5 | Take profit fisso +€100 | -€2.217,33 | +€186,37 |
| 6 | Pareggio dopo +€50 | -€2.336,10 | +€67,61 |
| 7 | Strategia attuale | -€2.403,71 | €0,00 |
| 8 | Take profit fisso +€150 | -€2.403,71 | €0,00 |
| 9 | Take profit fisso +€200 | -€2.403,71 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€2.809,53 | -€405,82 |
| 11 | Take profit fisso +€75 | -€2.822,39 | -€418,68 |
| 12 | TP +€50 / SL -€50 | -€4.165,23 | -€1.761,53 |
| 13 | Take profit fisso +€25 | -€4.831,36 | -€2.427,66 |
| 14 | Take profit fisso +€50 | -€5.351,36 | -€2.947,65 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
