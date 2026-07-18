# Analisi uscite paper trading a leva

Generato: 2026-07-18T21:38:35+00:00

> Analisi osservativa: non modifica ingressi, uscite o rischio del paper trading.

## Verifica del target +€50

- Trade chiusi: **217**
- Trade con percorso cronologico utilizzabile: **163**
- Trade che hanno raggiunto almeno +€50: **91**
- Di questi, chiusi poi in perdita: **16**

## Confronto simulazioni

| Posizione | Regola di uscita | P&L simulato | Differenza dall'attuale |
| ---: | --- | ---: | ---: |
| 1 | Protegge +€30 dopo +€50 | +€1.669,57 | +€204,48 |
| 2 | Protegge +€20 dopo +€50 | +€1.586,88 | +€121,79 |
| 3 | Stop loss fisso -€50 | +€1.572,86 | +€107,77 |
| 4 | Pareggio dopo +€50 | +€1.518,99 | +€53,90 |
| 5 | Strategia attuale | +€1.465,09 | €0,00 |
| 6 | Take profit fisso +€150 | +€1.465,09 | €0,00 |
| 7 | Take profit fisso +€200 | +€1.465,09 | €0,00 |
| 8 | Take profit fisso +€100 | +€1.443,89 | -€21,20 |
| 9 | Trailing 20% dopo +€50 | +€1.154,02 | -€311,07 |
| 10 | Chiude 50% a +€50 | +€1.154,02 | -€311,07 |
| 11 | Take profit fisso +€75 | +€900,62 | -€564,47 |
| 12 | TP +€50 / SL -€50 | +€195,24 | -€1.269,85 |
| 13 | Take profit fisso +€50 | +€71,48 | -€1.393,61 |
| 14 | Take profit fisso +€25 | -€485,90 | -€1.950,99 |

## Limiti metodologici

Le simulazioni usano i campioni cronologici salvati a ogni ciclo. Non presumono l'ordine interno dei movimenti tra due campioni. Le decisioni operative restano invariate finché il campione non sarà sufficiente.
