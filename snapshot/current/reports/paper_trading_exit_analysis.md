# Analisi uscite paper trading a leva

Generato: 2026-07-27T19:24:41+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2611**
- Trade con percorso cronologico utilizzabile: **2557**
- Trade che hanno raggiunto almeno +€50: **1126**
- Di questi, chiusi poi in perdita: **208**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.115,94 | +€9.632,86 |
| 2 | Protegge +€30 dopo +€50 | +€417,76 | +€934,68 |
| 3 | Chiude 50% a +€50 | +€64,81 | +€581,73 |
| 4 | Protegge +€20 dopo +€50 | -€480,17 | +€36,75 |
| 5 | Strategia attuale | -€516,92 | €0,00 |
| 6 | Take profit fisso +€200 | -€516,92 | €0,00 |
| 7 | Take profit fisso +€150 | -€521,24 | -€4,32 |
| 8 | Take profit fisso +€100 | -€601,12 | -€84,19 |
| 9 | Trailing 20% dopo +€50 | -€757,50 | -€240,58 |
| 10 | Pareggio dopo +€50 | -€1.311,10 | -€794,18 |
| 11 | TP +€50 / SL -€50 | -€2.334,78 | -€1.817,86 |
| 12 | Take profit fisso +€75 | -€4.552,43 | -€4.035,51 |
| 13 | Take profit fisso +€50 | -€11.829,51 | -€11.312,59 |
| 14 | Take profit fisso +€25 | -€14.779,67 | -€14.262,74 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
