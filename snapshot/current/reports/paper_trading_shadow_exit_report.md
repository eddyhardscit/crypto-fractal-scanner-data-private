# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T16:23:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **281**
- Scenari virtuali ancora attivi: **3009**
- Gruppi in attesa dell'uscita originale: **171**
- Gruppi con originale chiuso ma Shadow ancora attive: **110**
- Confronti completati: **8908**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 411 | 472 | +€7,38 | 47,0% | 114 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 411 | 472 | +€5,68 | 45,8% | 113 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 411 | 472 | +€3,71 | 45,1% | 114 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 411 | 472 | +€2,81 | 45,1% | 123 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 411 | 472 | +€1,85 | 44,3% | 109 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 409 | 470 | +€1,38 | 36,6% | 104 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 404 | 465 | €-0,91 | 51,6% | 99 | 50 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 397 | 458 | +€2,42 | 36,7% | 96 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 397 | 458 | +€1,31 | 36,0% | 88 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 396 | 457 | +€0,28 | 35,9% | 69 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 393 | 454 | +€1,92 | 30,0% | 47 | 46 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 390 | 451 | +€6,52 | 49,4% | 39 | 74 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 386 | 447 | €-2,86 | 28,4% | 32 | 100 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 374 | 435 | €-1,42 | 32,2% | 44 | 72 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 367 | 427 | €-7,57 | 28,1% | 73 | 51 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 359 | 420 | +€4,15 | 34,5% | 19 | 53 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 357 | 418 | €-2,20 | 31,8% | 20 | 101 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 355 | 416 | €-6,91 | 23,6% | 27 | 102 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 330 | 391 | €-11,79 | 21,2% | 24 | 92 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 322 | 381 | €-14,14 | 19,9% | 23 | 88 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
