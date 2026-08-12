# Analisi uscite paper trading a leva

Generato: 2026-08-12T19:43:40+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4570**
- Trade con percorso cronologico utilizzabile: **4516**
- Trade che hanno raggiunto almeno +€50: **1698**
- Di questi, chiusi poi in perdita: **350**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€8.215,32 | +€16.409,64 |
| 2 | TP +€50 / SL -€50 | -€17.658,77 | +€6.966,19 |
| 3 | Chiude 50% a +€50 | -€19.612,63 | +€5.012,33 |
| 4 | Protegge +€30 dopo +€50 | -€20.126,18 | +€4.498,78 |
| 5 | Protegge +€20 dopo +€50 | -€22.240,53 | +€2.384,43 |
| 6 | Strategia attuale | -€24.624,96 | €0,00 |
| 7 | Take profit fisso +€200 | -€24.624,96 | €0,00 |
| 8 | Take profit fisso +€150 | -€24.629,28 | -€4,32 |
| 9 | Take profit fisso +€100 | -€24.969,47 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€25.047,17 | -€422,21 |
| 11 | Pareggio dopo +€50 | -€26.127,97 | -€1.503,01 |
| 12 | Take profit fisso +€75 | -€28.276,73 | -€3.651,77 |
| 13 | Take profit fisso +€50 | -€33.875,70 | -€9.250,74 |
| 14 | Take profit fisso +€25 | -€36.514,73 | -€11.889,77 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
