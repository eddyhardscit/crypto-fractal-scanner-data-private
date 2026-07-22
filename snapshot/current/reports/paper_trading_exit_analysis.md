# Analisi uscite paper trading a leva

Generato: 2026-07-22T09:08:47+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **720**
- Trade con percorso cronologico utilizzabile: **666**
- Trade che hanno raggiunto almeno +€50: **279**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€2.065,43 | +€1.369,25 |
| 2 | Protegge +€30 dopo +€50 | -€2.907,12 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€3.104,47 | +€330,22 |
| 4 | Take profit fisso +€100 | -€3.253,81 | +€180,88 |
| 5 | Chiude 50% a +€50 | -€3.319,77 | +€114,91 |
| 6 | Pareggio dopo +€50 | -€3.367,07 | +€67,61 |
| 7 | Strategia attuale | -€3.434,68 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.434,68 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.434,68 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€3.904,80 | -€470,12 |
| 11 | Take profit fisso +€75 | -€3.988,55 | -€553,86 |
| 12 | TP +€50 / SL -€50 | -€5.288,53 | -€1.853,85 |
| 13 | Take profit fisso +€25 | -€5.830,06 | -€2.395,37 |
| 14 | Take profit fisso +€50 | -€6.673,78 | -€3.239,10 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
