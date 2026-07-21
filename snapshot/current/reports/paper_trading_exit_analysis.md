# Analisi uscite paper trading a leva

Generato: 2026-07-21T18:53:45+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **556**
- Trade con percorso cronologico utilizzabile: **502**
- Trade che hanno raggiunto almeno +€50: **243**
- Di questi, chiusi poi in perdita: **60**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€566,69 | +€888,21 |
| 2 | Protegge +€30 dopo +€50 | +€208,29 | +€529,80 |
| 3 | Chiude 50% a +€50 | -€2,74 | +€318,77 |
| 4 | Protegge +€20 dopo +€50 | -€32,30 | +€289,21 |
| 5 | Take profit fisso +€100 | -€134,74 | +€186,77 |
| 6 | Pareggio dopo +€50 | -€254,91 | +€66,61 |
| 7 | Strategia attuale | -€321,51 | €0,00 |
| 8 | Take profit fisso +€150 | -€321,51 | €0,00 |
| 9 | Take profit fisso +€200 | -€321,51 | €0,00 |
| 10 | Take profit fisso +€75 | -€779,51 | -€458,00 |
| 11 | Trailing 20% dopo +€50 | -€796,53 | -€475,01 |
| 12 | TP +€50 / SL -€50 | -€2.052,28 | -€1.730,77 |
| 13 | Take profit fisso +€50 | -€2.956,48 | -€2.634,97 |
| 14 | Take profit fisso +€25 | -€3.532,96 | -€3.211,45 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
