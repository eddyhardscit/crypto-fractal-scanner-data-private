# Analisi uscite paper trading a leva

Generato: 2026-08-11T19:30:10+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **4027**
- Trade con percorso cronologico utilizzabile: **3973**
- Trade che hanno raggiunto almeno +€50: **1583**
- Di questi, chiusi poi in perdita: **299**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Stop loss fisso -€50 | +€6.213,98 | +€13.940,24 |
| 2 | Chiude 50% a +€50 | -€4.789,52 | +€2.936,73 |
| 3 | Protegge +€30 dopo +€50 | -€5.531,22 | +€2.195,03 |
| 4 | TP +€50 / SL -€50 | -€5.748,69 | +€1.977,57 |
| 5 | Protegge +€20 dopo +€50 | -€7.158,95 | +€567,30 |
| 6 | Strategia attuale | -€7.726,25 | €0,00 |
| 7 | Take profit fisso +€200 | -€7.726,25 | €0,00 |
| 8 | Take profit fisso +€150 | -€7.730,57 | -€4,32 |
| 9 | Take profit fisso +€100 | -€8.070,77 | -€344,52 |
| 10 | Trailing 20% dopo +€50 | -€9.284,22 | -€1.557,97 |
| 11 | Pareggio dopo +€50 | -€10.206,01 | -€2.479,76 |
| 12 | Take profit fisso +€75 | -€11.676,84 | -€3.950,58 |
| 13 | Take profit fisso +€50 | -€19.549,87 | -€11.823,62 |
| 14 | Take profit fisso +€25 | -€22.917,51 | -€15.191,26 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
