# Analisi uscite paper trading a leva

Generato: 2026-07-20T04:08:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **315**
- Trade con percorso cronologico utilizzabile: **261**
- Trade che hanno raggiunto almeno +€50: **136**
- Di questi, chiusi poi in perdita: **30**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.003,00 | +€329,21 |
| 2 | Stop loss fisso -€50 | +€1.902,42 | +€228,64 |
| 3 | Protegge +€20 dopo +€50 | +€1.840,72 | +€166,93 |
| 4 | Take profit fisso +€100 | +€1.746,18 | +€72,39 |
| 5 | Pareggio dopo +€50 | +€1.729,86 | +€56,07 |
| 6 | Strategia attuale | +€1.673,79 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.673,79 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.673,79 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.423,51 | -€250,28 |
| 10 | Trailing 20% dopo +€50 | +€1.113,50 | -€560,29 |
| 11 | Take profit fisso +€75 | +€888,72 | -€785,07 |
| 12 | TP +€50 / SL -€50 | -€39,05 | -€1.712,83 |
| 13 | Take profit fisso +€50 | -€283,67 | -€1.957,46 |
| 14 | Take profit fisso +€25 | -€763,65 | -€2.437,44 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
