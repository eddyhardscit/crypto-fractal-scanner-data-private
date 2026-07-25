# Analisi uscite paper trading a leva

Generato: 2026-07-25T01:09:17+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1245**
- Trade con percorso cronologico utilizzabile: **1191**
- Trade che hanno raggiunto almeno +€50: **571**
- Di questi, chiusi poi in perdita: **133**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€1.447,08 | +€2.751,27 |
| 2 | Chiude 50% a +€50 | +€196,20 | +€1.500,38 |
| 3 | Take profit fisso +€100 | -€1.016,20 | +€287,99 |
| 4 | Strategia attuale | -€1.304,18 | €0,00 |
| 5 | Take profit fisso +€150 | -€1.304,18 | €0,00 |
| 6 | Take profit fisso +€200 | -€1.304,18 | €0,00 |
| 7 | Protegge +€30 dopo +€50 | -€1.409,14 | -€104,96 |
| 8 | Protegge +€20 dopo +€50 | -€1.736,07 | -€431,89 |
| 9 | Take profit fisso +€75 | -€2.351,32 | -€1.047,13 |
| 10 | Pareggio dopo +€50 | -€2.477,73 | -€1.173,54 |
| 11 | Trailing 20% dopo +€50 | -€2.636,27 | -€1.332,08 |
| 12 | TP +€50 / SL -€50 | -€3.588,76 | -€2.284,58 |
| 13 | Take profit fisso +€50 | -€6.356,02 | -€5.051,84 |
| 14 | Take profit fisso +€25 | -€6.709,43 | -€5.405,25 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
