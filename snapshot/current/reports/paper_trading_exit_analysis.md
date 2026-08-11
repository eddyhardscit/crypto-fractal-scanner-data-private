# Analisi uscite paper trading a leva

Generato: 2026-08-11T11:16:55+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3708**
- Trade con percorso cronologico utilizzabile: **3654**
- Trade che hanno raggiunto almeno +€50: **1445**
- Di questi, chiusi poi in perdita: **291**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.928,84 | +€12.384,42 |
| 2 | Chiude 50% a +€50 | -€2.928,59 | +€2.526,99 |
| 3 | Protegge +€30 dopo +€50 | -€3.684,76 | +€1.770,81 |
| 4 | Protegge +€20 dopo +€50 | -€4.621,05 | +€834,52 |
| 5 | TP +€50 / SL -€50 | -€5.262,10 | +€193,48 |
| 6 | Strategia attuale | -€5.455,57 | €0,00 |
| 7 | Take profit fisso +€200 | -€5.455,57 | €0,00 |
| 8 | Take profit fisso +€150 | -€5.459,89 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€5.756,27 | -€300,69 |
| 10 | Take profit fisso +€100 | -€5.823,13 | -€367,56 |
| 11 | Pareggio dopo +€50 | -€6.577,56 | -€1.121,99 |
| 12 | Take profit fisso +€75 | -€9.590,71 | -€4.135,14 |
| 13 | Take profit fisso +€50 | -€17.507,46 | -€12.051,89 |
| 14 | Take profit fisso +€25 | -€18.242,45 | -€12.786,88 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
