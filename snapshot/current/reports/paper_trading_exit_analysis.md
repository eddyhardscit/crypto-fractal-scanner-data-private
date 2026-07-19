# Analisi uscite paper trading a leva

Generato: 2026-07-19T13:53:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **263**
- Trade con percorso cronologico utilizzabile: **209**
- Trade che hanno raggiunto almeno +€50: **114**
- Di questi, chiusi poi in perdita: **26**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.906,01 | +€327,00 |
| 2 | Protegge +€20 dopo +€50 | +€1.783,74 | +€204,73 |
| 3 | Stop loss fisso -€50 | +€1.719,25 | +€140,24 |
| 4 | Take profit fisso +€100 | +€1.678,80 | +€99,78 |
| 5 | Pareggio dopo +€50 | +€1.635,85 | +€56,83 |
| 6 | Strategia attuale | +€1.579,01 | €0,00 |
| 7 | Take profit fisso +€150 | +€1.579,01 | €0,00 |
| 8 | Take profit fisso +€200 | +€1.579,01 | €0,00 |
| 9 | Chiude 50% a +€50 | +€1.382,32 | -€196,69 |
| 10 | Trailing 20% dopo +€50 | +€1.182,90 | -€396,11 |
| 11 | Take profit fisso +€75 | +€1.013,23 | -€565,79 |
| 12 | TP +€50 / SL -€50 | +€175,60 | -€1.403,42 |
| 13 | Take profit fisso +€50 | +€19,37 | -€1.559,64 |
| 14 | Take profit fisso +€25 | -€688,15 | -€2.267,16 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
