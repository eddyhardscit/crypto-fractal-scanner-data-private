# Analisi uscite paper trading a leva

Generato: 2026-07-19T07:53:34+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **239**
- Trade con percorso cronologico utilizzabile: **185**
- Trade che hanno raggiunto almeno +€50: **104**
- Di questi, chiusi poi in perdita: **19**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.168,28 | +€265,54 |
| 2 | Protegge +€20 dopo +€50 | +€2.066,01 | +€163,27 |
| 3 | Stop loss fisso -€50 | +€2.020,79 | +€118,06 |
| 4 | Pareggio dopo +€50 | +€1.958,12 | +€55,38 |
| 5 | Strategia attuale | +€1.902,73 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.902,73 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.902,73 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.872,65 | -€30,08 |
| 9 | Chiude 50% a +€50 | +€1.566,53 | -€336,20 |
| 10 | Trailing 20% dopo +€50 | +€1.420,86 | -€481,87 |
| 11 | Take profit fisso +€75 | +€1.206,38 | -€696,35 |
| 12 | TP +€50 / SL -€50 | +€458,03 | -€1.444,70 |
| 13 | Take profit fisso +€50 | +€323,98 | -€1.578,76 |
| 14 | Take profit fisso +€25 | -€342,04 | -€2.244,77 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
