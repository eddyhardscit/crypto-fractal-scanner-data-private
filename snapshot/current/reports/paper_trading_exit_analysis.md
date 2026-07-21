# Analisi uscite paper trading a leva

Generato: 2026-07-21T09:38:42+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **448**
- Trade con percorso cronologico utilizzabile: **394**
- Trade che hanno raggiunto almeno +€50: **189**
- Di questi, chiusi poi in perdita: **47**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€405,54 | +€604,22 |
| 2 | Protegge +€30 dopo +€50 | +€307,86 | +€506,54 |
| 3 | Protegge +€20 dopo +€50 | +€97,27 | +€295,96 |
| 4 | Chiude 50% a +€50 | -€80,08 | +€118,60 |
| 5 | Take profit fisso +€100 | -€93,26 | +€105,42 |
| 6 | Pareggio dopo +€50 | -€132,08 | +€66,61 |
| 7 | Strategia attuale | -€198,68 | €0,00 |
| 8 | Take profit fisso +€150 | -€198,68 | €0,00 |
| 9 | Take profit fisso +€200 | -€198,68 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€492,15 | -€293,47 |
| 11 | Take profit fisso +€75 | -€993,11 | -€794,43 |
| 12 | TP +€50 / SL -€50 | -€1.859,03 | -€1.660,34 |
| 13 | Take profit fisso +€50 | -€2.479,24 | -€2.280,56 |
| 14 | Take profit fisso +€25 | -€2.815,63 | -€2.616,95 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
