# Analisi uscite paper trading a leva

Generato: 2026-07-25T20:24:18+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **1515**
- Trade con percorso cronologico utilizzabile: **1461**
- Trade che hanno raggiunto almeno +€50: **730**
- Di questi, chiusi poi in perdita: **157**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.071,08 | +€4.043,33 |
| 2 | Chiude 50% a +€50 | +€4.522,73 | +€494,97 |
| 3 | Protegge +€20 dopo +€50 | +€4.072,10 | +€44,35 |
| 4 | Strategia attuale | +€4.027,75 | €0,00 |
| 5 | Take profit fisso +€200 | +€4.027,75 | €0,00 |
| 6 | Take profit fisso +€150 | +€4.027,01 | -€0,74 |
| 7 | Protegge +€30 dopo +€50 | +€4.001,53 | -€26,22 |
| 8 | Take profit fisso +€100 | +€3.991,12 | -€36,63 |
| 9 | Pareggio dopo +€50 | +€3.146,91 | -€880,84 |
| 10 | Trailing 20% dopo +€50 | +€2.528,72 | -€1.499,03 |
| 11 | Take profit fisso +€75 | +€1.477,06 | -€2.550,69 |
| 12 | TP +€50 / SL -€50 | -€144,15 | -€4.171,90 |
| 13 | Take profit fisso +€50 | -€4.049,34 | -€8.077,10 |
| 14 | Take profit fisso +€25 | -€7.009,41 | -€11.037,17 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
