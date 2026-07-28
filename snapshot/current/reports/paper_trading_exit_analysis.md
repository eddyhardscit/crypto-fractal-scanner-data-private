# Analisi uscite paper trading a leva

Generato: 2026-07-28T06:40:22+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **2846**
- Trade con percorso cronologico utilizzabile: **2792**
- Trade che hanno raggiunto almeno +€50: **1225**
- Di questi, chiusi poi in perdita: **240**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€9.951,99 | +€10.919,78 |
| 2 | Protegge +€30 dopo +€50 | +€713,15 | +€1.680,95 |
| 3 | Chiude 50% a +€50 | +€371,09 | +€1.338,88 |
| 4 | Protegge +€20 dopo +€50 | -€311,91 | +€655,88 |
| 5 | Strategia attuale | -€967,79 | €0,00 |
| 6 | Take profit fisso +€200 | -€967,79 | €0,00 |
| 7 | Take profit fisso +€150 | -€972,11 | -€4,32 |
| 8 | Trailing 20% dopo +€50 | -€1.007,92 | -€40,13 |
| 9 | Take profit fisso +€100 | -€1.080,65 | -€112,86 |
| 10 | TP +€50 / SL -€50 | -€1.340,46 | -€372,67 |
| 11 | Pareggio dopo +€50 | -€1.540,70 | -€572,91 |
| 12 | Take profit fisso +€75 | -€5.098,63 | -€4.130,84 |
| 13 | Take profit fisso +€50 | -€12.122,11 | -€11.154,32 |
| 14 | Take profit fisso +€25 | -€14.010,26 | -€13.042,47 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
