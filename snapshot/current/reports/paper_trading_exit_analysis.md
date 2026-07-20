# Analisi uscite paper trading a leva

Generato: 2026-07-20T10:23:37+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **356**
- Trade con percorso cronologico utilizzabile: **302**
- Trade che hanno raggiunto almeno +€50: **161**
- Di questi, chiusi poi in perdita: **38**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.156,39 | +€433,98 |
| 2 | Stop loss fisso -€50 | +€2.009,00 | +€286,59 |
| 3 | Protegge +€20 dopo +€50 | +€1.975,80 | +€253,39 |
| 4 | Pareggio dopo +€50 | +€1.788,81 | +€66,40 |
| 5 | Take profit fisso +€100 | +€1.754,80 | +€32,39 |
| 6 | Strategia attuale | +€1.722,41 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.722,41 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.722,41 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.692,50 | -€29,91 |
| 10 | Trailing 20% dopo +€50 | +€1.327,97 | -€394,44 |
| 11 | Take profit fisso +€75 | +€953,46 | -€768,95 |
| 12 | TP +€50 / SL -€50 | +€37,54 | -€1.684,86 |
| 13 | Take profit fisso +€50 | -€265,04 | -€1.987,45 |
| 14 | Take profit fisso +€25 | -€742,72 | -€2.465,13 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
