# Analisi uscite paper trading a leva

Generato: 2026-07-19T09:53:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **249**
- Trade con percorso cronologico utilizzabile: **195**
- Trade che hanno raggiunto almeno +€50: **105**
- Di questi, chiusi poi in perdita: **20**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.861,86 | +€296,30 |
| 2 | Protegge +€20 dopo +€50 | +€1.749,59 | +€184,03 |
| 3 | Stop loss fisso -€50 | +€1.697,07 | +€131,51 |
| 4 | Take profit fisso +€100 | +€1.636,23 | +€70,67 |
| 5 | Pareggio dopo +€50 | +€1.621,70 | +€56,14 |
| 6 | Strategia attuale | +€1.565,56 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.565,56 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.565,56 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.254,74 | -€310,82 |
| 10 | Trailing 20% dopo +€50 | +€1.122,59 | -€442,97 |
| 11 | Take profit fisso +€75 | +€944,97 | -€620,59 |
| 12 | TP +€50 / SL -€50 | +€185,06 | -€1.380,50 |
| 13 | Take profit fisso +€50 | +€37,56 | -€1.528,00 |
| 14 | Take profit fisso +€25 | -€653,45 | -€2.219,01 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
