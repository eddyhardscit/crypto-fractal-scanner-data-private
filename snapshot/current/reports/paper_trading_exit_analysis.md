# Analisi uscite paper trading a leva

Generato: 2026-07-18T13:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **188**
- Trade con percorso cronologico utilizzabile: **134**
- Trade che hanno raggiunto almeno +€50: **86**
- Di questi, chiusi poi in perdita: **14**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.525,26 | +€189,46 |
| 2 | Protegge +€20 dopo +€50 | +€2.452,57 | +€116,77 |
| 3 | Stop loss fisso -€50 | +€2.416,77 | +€80,97 |
| 4 | Pareggio dopo +€50 | +€2.389,70 | +€53,90 |
| 5 | Strategia attuale | +€2.335,80 | €0,00 |
| 6 | Take profit fisso +€150 | +€2.335,80 | €0,00 |
| 7 | Take profit fisso +€200 | +€2.335,80 | €0,00 |
| 8 | Take profit fisso +€100 | +€2.314,60 | -€21,20 |
| 9 | Trailing 20% dopo +€50 | +€1.997,00 | -€338,80 |
| 10 | Chiude 50% a +€50 | +€1.954,97 | -€380,83 |
| 11 | Take profit fisso +€75 | +€1.771,33 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€1.028,12 | -€1.307,68 |
| 13 | Take profit fisso +€50 | +€931,15 | -€1.404,65 |
| 14 | Take profit fisso +€25 | -€59,95 | -€2.395,75 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
