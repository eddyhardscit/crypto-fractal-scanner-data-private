# Analisi uscite paper trading a leva

Generato: 2026-07-18T16:38:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **199**
- Trade con percorso cronologico utilizzabile: **145**
- Trade che hanno raggiunto almeno +€50: **87**
- Di questi, chiusi poi in perdita: **14**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€2.041,64 | +€204,48 |
| 2 | Protegge +€20 dopo +€50 | +€1.958,95 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€1.931,75 | +€94,59 |
| 4 | Pareggio dopo +€50 | +€1.891,06 | +€53,90 |
| 5 | Strategia attuale | +€1.837,16 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.837,16 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.837,16 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.815,96 | -€21,20 |
| 9 | Trailing 20% dopo +€50 | +€1.526,09 | -€311,07 |
| 10 | Chiude 50% a +€50 | +€1.473,84 | -€363,32 |
| 11 | Take profit fisso +€75 | +€1.272,69 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€578,12 | -€1.259,04 |
| 13 | Take profit fisso +€50 | +€467,53 | -€1.369,63 |
| 14 | Take profit fisso +€25 | -€548,57 | -€2.385,73 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
