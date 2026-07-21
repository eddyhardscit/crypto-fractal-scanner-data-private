# Analisi uscite paper trading a leva

Generato: 2026-07-21T17:53:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **545**
- Trade con percorso cronologico utilizzabile: **491**
- Trade che hanno raggiunto almeno +€50: **235**
- Di questi, chiusi poi in perdita: **60**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€263,41 | +€882,62 |
| 2 | Protegge +€30 dopo +€50 | -€89,41 | +€529,80 |
| 3 | Chiude 50% a +€50 | -€315,97 | +€303,24 |
| 4 | Protegge +€20 dopo +€50 | -€330,00 | +€289,21 |
| 5 | Take profit fisso +€100 | -€432,44 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€552,61 | +€66,61 |
| 7 | Strategia attuale | -€619,21 | €0,00 |
| 8 | Take profit fisso +€150 | -€619,21 | €0,00 |
| 9 | Take profit fisso +€200 | -€619,21 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€1.038,65 | -€419,43 |
| 11 | Take profit fisso +€75 | -€1.163,05 | -€543,84 |
| 12 | TP +€50 / SL -€50 | -€2.338,49 | -€1.719,27 |
| 13 | Take profit fisso +€50 | -€3.237,10 | -€2.617,89 |
| 14 | Take profit fisso +€25 | -€3.687,46 | -€3.068,25 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
