# Analisi uscite paper trading a leva

Generato: 2026-07-28T18:55:08+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3200**
- Trade con percorso cronologico utilizzabile: **3146**
- Trade che hanno raggiunto almeno +€50: **1331**
- Di questi, chiusi poi in perdita: **274**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€8.917,48 | +€11.308,88 |
| 2 | Chiude 50% a +€50 | -€196,02 | +€2.195,38 |
| 3 | Protegge +€30 dopo +€50 | -€1.176,40 | +€1.215,00 |
| 4 | Protegge +€20 dopo +€50 | -€1.940,12 | +€451,28 |
| 5 | Strategia attuale | -€2.391,40 | €0,00 |
| 6 | Take profit fisso +€200 | -€2.391,40 | €0,00 |
| 7 | Take profit fisso +€150 | -€2.395,72 | -€4,32 |
| 8 | Take profit fisso +€100 | -€2.598,43 | -€207,03 |
| 9 | TP +€50 / SL -€50 | -€2.634,53 | -€243,13 |
| 10 | Trailing 20% dopo +€50 | -€2.711,60 | -€320,20 |
| 11 | Pareggio dopo +€50 | -€3.571,42 | -€1.180,02 |
| 12 | Take profit fisso +€75 | -€6.869,94 | -€4.478,54 |
| 13 | Take profit fisso +€50 | -€13.805,29 | -€11.413,88 |
| 14 | Take profit fisso +€25 | -€14.500,51 | -€12.109,11 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
