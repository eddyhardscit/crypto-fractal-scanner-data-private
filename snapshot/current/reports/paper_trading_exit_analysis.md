# Analisi uscite paper trading a leva

Generato: 2026-07-21T10:38:44+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **455**
- Trade con percorso cronologico utilizzabile: **401**
- Trade che hanno raggiunto almeno +€50: **189**
- Di questi, chiusi poi in perdita: **47**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€55,54 | +€779,11 |
| 2 | Protegge +€30 dopo +€50 | -€217,02 | +€506,54 |
| 3 | Protegge +€20 dopo +€50 | -€427,61 | +€295,96 |
| 4 | Chiude 50% a +€50 | -€604,97 | +€118,60 |
| 5 | Take profit fisso +€100 | -€618,14 | +€105,42 |
| 6 | Pareggio dopo +€50 | -€656,96 | +€66,61 |
| 7 | Strategia attuale | -€723,57 | €0,00 |
| 8 | Take profit fisso +€150 | -€723,57 | €0,00 |
| 9 | Take profit fisso +€200 | -€723,57 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€1.017,04 | -€293,47 |
| 11 | Take profit fisso +€75 | -€1.517,99 | -€794,43 |
| 12 | TP +€50 / SL -€50 | -€2.209,03 | -€1.485,46 |
| 13 | Take profit fisso +€50 | -€3.004,13 | -€2.280,56 |
| 14 | Take profit fisso +€25 | -€3.055,47 | -€2.331,90 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
