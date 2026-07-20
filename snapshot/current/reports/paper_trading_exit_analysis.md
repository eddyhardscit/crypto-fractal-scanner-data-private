# Analisi uscite paper trading a leva

Generato: 2026-07-20T16:23:37+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **395**
- Trade con percorso cronologico utilizzabile: **341**
- Trade che hanno raggiunto almeno +€50: **168**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.266,18 | +€449,20 |
| 2 | Stop loss fisso -€50 | +€1.182,50 | +€365,53 |
| 3 | Protegge +€20 dopo +€50 | +€1.075,59 | +€258,62 |
| 4 | Pareggio dopo +€50 | +€883,37 | +€66,40 |
| 5 | Take profit fisso +€100 | +€840,12 | +€23,14 |
| 6 | Strategia attuale | +€816,97 | €0,00 |
| 7 | Take profit fisso +€150 | +€816,97 | €0,00 |
| 8 | Take profit fisso +€200 | +€816,97 | €0,00 |
| 9 | Chiude 50% a +€50 | +€705,48 | -€111,49 |
| 10 | Trailing 20% dopo +€50 | +€445,80 | -€371,18 |
| 11 | Take profit fisso +€75 | -€6,59 | -€823,57 |
| 12 | TP +€50 / SL -€50 | -€952,10 | -€1.769,07 |
| 13 | Take profit fisso +€50 | -€1.333,62 | -€2.150,60 |
| 14 | Take profit fisso +€25 | -€1.826,70 | -€2.643,67 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
