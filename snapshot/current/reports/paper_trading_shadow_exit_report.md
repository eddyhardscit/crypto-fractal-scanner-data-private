# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T12:08:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **262**
- Scenari virtuali ancora attivi: **2976**
- Gruppi in attesa dell'uscita originale: **162**
- Gruppi con originale chiuso ma Shadow ancora attive: **100**
- Confronti completati: **8563**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 392 | 451 | +€7,84 | 47,5% | 106 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 392 | 451 | +€5,89 | 46,1% | 105 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 392 | 451 | +€3,96 | 45,5% | 106 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 392 | 451 | +€3,23 | 45,5% | 115 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 392 | 451 | +€2,17 | 44,6% | 101 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 383 | 442 | +€2,34 | 37,1% | 89 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 383 | 442 | +€1,33 | 36,4% | 81 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 383 | 442 | +€0,43 | 36,4% | 62 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 383 | 442 | +€0,09 | 35,5% | 96 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 382 | 441 | +€6,38 | 49,7% | 39 | 71 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 382 | 441 | €-1,25 | 51,0% | 92 | 48 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 378 | 437 | €-3,49 | 27,9% | 32 | 100 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 367 | 426 | €-0,64 | 28,4% | 46 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 359 | 418 | €-1,27 | 32,5% | 37 | 71 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 355 | 413 | €-7,62 | 29,1% | 71 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 349 | 408 | +€4,12 | 35,3% | 19 | 49 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 349 | 408 | €-7,46 | 23,5% | 27 | 101 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 335 | 394 | €-5,79 | 30,5% | 20 | 95 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 322 | 381 | €-11,87 | 21,8% | 24 | 89 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 316 | 373 | €-14,42 | 20,4% | 23 | 87 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
