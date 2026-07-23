# Analisi uscite paper trading a leva

Generato: 2026-07-23T15:38:50+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **895**
- Trade con percorso cronologico utilizzabile: **841**
- Trade che hanno raggiunto almeno +€50: **355**
- Di questi, chiusi poi in perdita: **81**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.373,76 | +€1.700,96 |
| 2 | Protegge +€20 dopo +€50 | -€3.740,09 | +€334,63 |
| 3 | Chiude 50% a +€50 | -€3.778,84 | +€295,87 |
| 4 | Take profit fisso +€100 | -€3.866,22 | +€208,50 |
| 5 | Protegge +€30 dopo +€50 | -€3.879,60 | +€195,12 |
| 6 | Pareggio dopo +€50 | -€3.995,59 | +€79,13 |
| 7 | Strategia attuale | -€4.074,72 | €0,00 |
| 8 | Take profit fisso +€150 | -€4.074,72 | €0,00 |
| 9 | Take profit fisso +€200 | -€4.074,72 | €0,00 |
| 10 | Take profit fisso +€75 | -€4.632,37 | -€557,65 |
| 11 | Trailing 20% dopo +€50 | -€4.789,25 | -€714,53 |
| 12 | TP +€50 / SL -€50 | -€6.515,26 | -€2.440,55 |
| 13 | Take profit fisso +€25 | -€7.022,75 | -€2.948,03 |
| 14 | Take profit fisso +€50 | -€8.232,21 | -€4.157,49 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
