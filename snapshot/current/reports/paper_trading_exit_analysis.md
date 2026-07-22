# Analisi uscite paper trading a leva

Generato: 2026-07-22T11:08:46+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **726**
- Trade con percorso cronologico utilizzabile: **672**
- Trade che hanno raggiunto almeno +€50: **283**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.731,58 | +€1.374,90 |
| 2 | Protegge +€30 dopo +€50 | -€2.578,91 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€2.776,25 | +€330,22 |
| 4 | Take profit fisso +€100 | -€2.912,52 | +€193,95 |
| 5 | Pareggio dopo +€50 | -€3.038,86 | +€67,61 |
| 6 | Chiude 50% a +€50 | -€3.083,76 | +€22,71 |
| 7 | Strategia attuale | -€3.106,47 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.106,47 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.106,47 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€3.565,78 | -€459,31 |
| 11 | Take profit fisso +€75 | -€3.744,73 | -€638,25 |
| 12 | TP +€50 / SL -€50 | -€5.139,07 | -€2.032,60 |
| 13 | Take profit fisso +€25 | -€5.786,24 | -€2.679,76 |
| 14 | Take profit fisso +€50 | -€6.529,96 | -€3.423,49 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
