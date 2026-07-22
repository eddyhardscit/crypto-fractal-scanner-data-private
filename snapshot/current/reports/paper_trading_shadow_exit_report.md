# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T19:23:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **274**
- Scenari virtuali ancora attivi: **2580**
- Gruppi in attesa dell'uscita originale: **152**
- Gruppi con originale chiuso ma Shadow ancora attive: **122**
- Confronti completati: **10161**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 468 | 529 | +€8,06 | 47,3% | 123 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 468 | 529 | +€6,28 | 46,1% | 123 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 468 | 529 | +€4,27 | 45,4% | 124 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 468 | 529 | +€3,42 | 45,7% | 132 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 468 | 529 | +€2,31 | 44,6% | 119 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 467 | 528 | €-1,13 | 49,8% | 109 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 461 | 522 | +€2,35 | 36,6% | 112 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 460 | 521 | +€4,71 | 38,0% | 104 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 460 | 521 | +€3,23 | 37,4% | 96 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 460 | 521 | +€1,88 | 37,4% | 76 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 458 | 519 | +€1,05 | 35,1% | 51 | 83 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 452 | 513 | €-2,97 | 29,2% | 33 | 111 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 446 | 507 | €-4,98 | 25,0% | 39 | 121 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 444 | 505 | +€2,61 | 44,2% | 41 | 102 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 432 | 493 | +€1,94 | 28,4% | 48 | 48 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 432 | 493 | €-7,98 | 22,3% | 35 | 114 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 424 | 485 | €-7,36 | 26,6% | 85 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 416 | 477 | €-2,90 | 30,2% | 22 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 403 | 464 | +€0,32 | 31,2% | 20 | 72 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 387 | 447 | €-13,64 | 17,2% | 34 | 100 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
