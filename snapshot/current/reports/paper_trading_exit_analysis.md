# Analisi uscite paper trading a leva

Generato: 2026-07-26T04:39:07+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1637**
- Trade con percorso cronologico utilizzabile: **1583**
- Trade che hanno raggiunto almeno +€50: **786**
- Di questi, chiusi poi in perdita: **168**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.463,47 | +€4.327,05 |
| 2 | Chiude 50% a +€50 | +€5.414,49 | +€278,07 |
| 3 | Protegge +€20 dopo +€50 | +€5.180,77 | +€44,35 |
| 4 | Strategia attuale | +€5.136,42 | €0,00 |
| 5 | Take profit fisso +€200 | +€5.136,42 | €0,00 |
| 6 | Take profit fisso +€150 | +€5.135,68 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€5.098,79 | -€37,63 |
| 8 | Take profit fisso +€100 | +€5.072,07 | -€64,35 |
| 9 | Pareggio dopo +€50 | +€4.255,58 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€3.496,78 | -€1.639,64 |
| 11 | Take profit fisso +€75 | +€2.252,66 | -€2.883,76 |
| 12 | TP +€50 / SL -€50 | +€30,68 | -€5.105,74 |
| 13 | Take profit fisso +€50 | -€4.158,24 | -€9.294,66 |
| 14 | Take profit fisso +€25 | -€7.646,27 | -€12.782,70 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
