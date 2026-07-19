# Analisi uscite paper trading a leva

Generato: 2026-07-19T11:53:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **255**
- Trade con percorso cronologico utilizzabile: **201**
- Trade che hanno raggiunto almeno +€50: **110**
- Di questi, chiusi poi in perdita: **22**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.036,81 | +€296,30 |
| 2 | Protegge +€20 dopo +€50 | +€1.924,54 | +€184,03 |
| 3 | Stop loss fisso -€50 | +€1.872,02 | +€131,51 |
| 4 | Take profit fisso +€100 | +€1.840,29 | +€99,78 |
| 5 | Pareggio dopo +€50 | +€1.796,65 | +€56,14 |
| 6 | Strategia attuale | +€1.740,51 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.740,51 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.740,51 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.442,47 | -€298,04 |
| 10 | Trailing 20% dopo +€50 | +€1.297,54 | -€442,97 |
| 11 | Take profit fisso +€75 | +€1.099,03 | -€641,48 |
| 12 | TP +€50 / SL -€50 | +€277,67 | -€1.462,84 |
| 13 | Take profit fisso +€50 | +€130,17 | -€1.610,34 |
| 14 | Take profit fisso +€25 | -€577,93 | -€2.318,44 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
