# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T18:23:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **115**
- Scenari virtuali ancora attivi: **1357**
- Gruppi in attesa dell'uscita originale: **71**
- Gruppi con originale chiuso ma Shadow ancora attive: **44**
- Confronti completati: **2246**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 83 | 119 | +€9,04 | 44,5% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 83 | 119 | +€6,81 | 43,7% | 24 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 83 | 119 | +€4,55 | 42,0% | 25 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 83 | 119 | +€3,73 | 41,2% | 21 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 83 | 119 | +€3,28 | 44,5% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 82 | 118 | +€7,83 | 39,0% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 82 | 118 | +€5,02 | 39,0% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 82 | 118 | +€4,75 | 38,1% | 22 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 82 | 118 | +€1,66 | 37,3% | 20 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 82 | 118 | +€0,33 | 35,6% | 12 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 81 | 123 | €-2,45 | 38,2% | 25 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 76 | 112 | +€0,23 | 25,0% | 15 | 13 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 75 | 111 | €-5,65 | 26,1% | 23 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 74 | 105 | +€3,64 | 26,7% | 9 | 14 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 72 | 108 | €-4,58 | 32,4% | 7 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 67 | 109 | +€2,45 | 30,3% | 17 | 13 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 67 | 100 | €-5,16 | 30,0% | 3 | 15 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 66 | 99 | €-7,16 | 22,2% | 3 | 21 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 66 | 99 | €-7,57 | 22,2% | 2 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 53 | 95 | €-2,46 | 26,3% | 10 | 13 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
