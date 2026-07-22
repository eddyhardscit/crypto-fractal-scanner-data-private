# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T11:08:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **260**
- Scenari virtuali ancora attivi: **2985**
- Gruppi in attesa dell'uscita originale: **160**
- Gruppi con originale chiuso ma Shadow ancora attive: **100**
- Confronti completati: **8471**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 388 | 447 | +€7,83 | 47,0% | 106 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 388 | 447 | +€5,87 | 45,6% | 105 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 388 | 447 | +€3,92 | 45,0% | 106 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 388 | 447 | +€3,18 | 45,0% | 115 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 388 | 447 | +€2,11 | 44,1% | 101 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 379 | 438 | +€2,29 | 36,5% | 89 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 379 | 438 | +€1,27 | 35,8% | 81 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 379 | 438 | +€0,36 | 35,8% | 62 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 379 | 438 | +€0,01 | 34,9% | 96 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 378 | 437 | €-1,34 | 50,6% | 92 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 377 | 436 | +€6,38 | 49,3% | 39 | 70 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 363 | 422 | €-0,73 | 27,7% | 46 | 46 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 363 | 422 | €-3,84 | 26,3% | 32 | 96 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 355 | 414 | €-1,36 | 31,9% | 37 | 71 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 351 | 409 | €-7,78 | 28,4% | 71 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 345 | 404 | +€4,08 | 34,7% | 19 | 49 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 345 | 404 | €-7,61 | 22,8% | 27 | 101 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 331 | 390 | €-5,93 | 29,7% | 20 | 95 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 318 | 377 | €-12,08 | 21,0% | 24 | 89 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 312 | 369 | €-14,67 | 19,5% | 23 | 87 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
