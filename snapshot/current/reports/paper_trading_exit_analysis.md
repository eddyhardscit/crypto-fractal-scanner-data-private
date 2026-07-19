# Analisi uscite paper trading a leva

Generato: 2026-07-19T01:38:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **226**
- Trade con percorso cronologico utilizzabile: **172**
- Trade che hanno raggiunto almeno +€50: **97**
- Di questi, chiusi poi in perdita: **17**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.131,54 | +€234,80 |
| 2 | Protegge +€20 dopo +€50 | +€2.039,27 | +€142,53 |
| 3 | Stop loss fisso -€50 | +€2.004,51 | +€107,77 |
| 4 | Pareggio dopo +€50 | +€1.951,38 | +€54,64 |
| 5 | Strategia attuale | +€1.896,74 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.896,74 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.896,74 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.864,71 | -€32,03 |
| 9 | Chiude 50% a +€50 | +€1.518,97 | -€377,77 |
| 10 | Trailing 20% dopo +€50 | +€1.442,46 | -€454,28 |
| 11 | Take profit fisso +€75 | +€1.228,55 | -€668,19 |
| 12 | TP +€50 / SL -€50 | +€493,50 | -€1.403,24 |
| 13 | Take profit fisso +€50 | +€369,74 | -€1.527,00 |
| 14 | Take profit fisso +€25 | -€311,90 | -€2.208,64 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
