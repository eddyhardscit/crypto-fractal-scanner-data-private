# Analisi uscite paper trading a leva

Generato: 2026-08-11T15:15:15+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **3908**
- Trade con percorso cronologico utilizzabile: **3854**
- Trade che hanno raggiunto almeno +€50: **1504**
- Di questi, chiusi poi in perdita: **297**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€4.717,98 | +€13.826,86 |
| 2 | Protegge +€30 dopo +€50 | -€6.853,99 | +€2.254,90 |
| 3 | Chiude 50% a +€50 | -€6.902,36 | +€2.206,52 |
| 4 | Protegge +€20 dopo +€50 | -€7.904,14 | +€1.204,74 |
| 5 | TP +€50 / SL -€50 | -€8.113,88 | +€995,00 |
| 6 | Strategia attuale | -€9.108,88 | €0,00 |
| 7 | Take profit fisso +€200 | -€9.108,88 | €0,00 |
| 8 | Take profit fisso +€150 | -€9.113,20 | -€4,32 |
| 9 | Trailing 20% dopo +€50 | -€9.266,04 | -€157,16 |
| 10 | Take profit fisso +€100 | -€9.392,94 | -€284,06 |
| 11 | Pareggio dopo +€50 | -€10.018,22 | -€909,34 |
| 12 | Take profit fisso +€75 | -€13.677,46 | -€4.568,57 |
| 13 | Take profit fisso +€50 | -€21.801,69 | -€12.692,81 |
| 14 | Take profit fisso +€25 | -€23.838,51 | -€14.729,63 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
