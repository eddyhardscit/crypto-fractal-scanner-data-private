# Analisi uscite paper trading a leva

Generato: 2026-07-22T12:08:47+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **730**
- Trade con percorso cronologico utilizzabile: **676**
- Trade che hanno raggiunto almeno +€50: **283**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.931,58 | +€1.411,59 |
| 2 | Protegge +€30 dopo +€50 | -€2.815,61 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€3.012,95 | +€330,22 |
| 4 | Take profit fisso +€100 | -€3.149,21 | +€193,95 |
| 5 | Pareggio dopo +€50 | -€3.275,56 | +€67,61 |
| 6 | Chiude 50% a +€50 | -€3.320,46 | +€22,71 |
| 7 | Strategia attuale | -€3.343,17 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.343,17 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.343,17 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€3.802,48 | -€459,31 |
| 11 | Take profit fisso +€75 | -€3.981,42 | -€638,25 |
| 12 | TP +€50 / SL -€50 | -€5.339,07 | -€1.995,90 |
| 13 | Take profit fisso +€25 | -€6.022,93 | -€2.679,76 |
| 14 | Take profit fisso +€50 | -€6.766,66 | -€3.423,49 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
