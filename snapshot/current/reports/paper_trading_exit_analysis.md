# Analisi uscite paper trading a leva

Generato: 2026-07-18T17:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **200**
- Trade con percorso cronologico utilizzabile: **146**
- Trade che hanno raggiunto almeno +€50: **88**
- Di questi, chiusi poi in perdita: **14**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.068,28 | +€204,48 |
| 2 | Protegge +€20 dopo +€50 | +€1.985,59 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€1.958,39 | +€94,59 |
| 4 | Pareggio dopo +€50 | +€1.917,70 | +€53,90 |
| 5 | Strategia attuale | +€1.863,80 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.863,80 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.863,80 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.842,60 | -€21,20 |
| 9 | Trailing 20% dopo +€50 | +€1.552,73 | -€311,07 |
| 10 | Chiude 50% a +€50 | +€1.512,16 | -€351,64 |
| 11 | Take profit fisso +€75 | +€1.299,33 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€604,76 | -€1.259,04 |
| 13 | Take profit fisso +€50 | +€494,17 | -€1.369,63 |
| 14 | Take profit fisso +€25 | -€523,57 | -€2.387,37 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
