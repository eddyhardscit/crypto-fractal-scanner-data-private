# Analisi uscite paper trading a leva

Generato: 2026-07-28T15:40:52+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3148**
- Trade con percorso cronologico utilizzabile: **3094**
- Trade che hanno raggiunto almeno +€50: **1317**
- Di questi, chiusi poi in perdita: **273**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.307,24 | +€11.276,89 |
| 2 | Chiude 50% a +€50 | +€301,68 | +€2.271,34 |
| 3 | Protegge +€30 dopo +€50 | -€785,26 | +€1.184,40 |
| 4 | Protegge +€20 dopo +€50 | -€1.538,98 | +€430,67 |
| 5 | Strategia attuale | -€1.969,66 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.969,66 | €0,00 |
| 7 | Take profit fisso +€150 | -€1.973,97 | -€4,32 |
| 8 | TP +€50 / SL -€50 | -€2.092,87 | -€123,21 |
| 9 | Take profit fisso +€100 | -€2.176,69 | -€207,03 |
| 10 | Trailing 20% dopo +€50 | -€2.276,70 | -€307,05 |
| 11 | Pareggio dopo +€50 | -€3.150,28 | -€1.180,63 |
| 12 | Take profit fisso +€75 | -€6.590,77 | -€4.621,11 |
| 13 | Take profit fisso +€50 | -€13.231,63 | -€11.261,97 |
| 14 | Take profit fisso +€25 | -€14.866,20 | -€12.896,54 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
