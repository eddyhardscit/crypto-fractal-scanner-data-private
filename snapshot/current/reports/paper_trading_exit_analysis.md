# Analisi uscite paper trading a leva

Generato: 2026-07-22T10:08:47+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **725**
- Trade con percorso cronologico utilizzabile: **671**
- Trade che hanno raggiunto almeno +€50: **282**
- Di questi, chiusi poi in perdita: **65**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | -€1.808,56 | +€1.374,90 |
| 2 | Protegge +€30 dopo +€50 | -€2.655,89 | +€527,56 |
| 3 | Protegge +€20 dopo +€50 | -€2.853,24 | +€330,22 |
| 4 | Take profit fisso +€100 | -€3.012,52 | +€170,93 |
| 5 | Pareggio dopo +€50 | -€3.115,84 | +€67,61 |
| 6 | Chiude 50% a +€50 | -€3.147,25 | +€36,20 |
| 7 | Strategia attuale | -€3.183,45 | €0,00 |
| 8 | Take profit fisso +€150 | -€3.183,45 | €0,00 |
| 9 | Take profit fisso +€200 | -€3.183,45 | €0,00 |
| 10 | Trailing 20% dopo +€50 | -€3.653,57 | -€470,12 |
| 11 | Take profit fisso +€75 | -€3.819,73 | -€636,27 |
| 12 | TP +€50 / SL -€50 | -€5.189,07 | -€2.005,62 |
| 13 | Take profit fisso +€25 | -€5.811,24 | -€2.627,78 |
| 14 | Take profit fisso +€50 | -€6.579,96 | -€3.396,51 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
