# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T12:38:57+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **769**
- Scenari virtuali ancora attivi: **16466**
- Gruppi in attesa dell'uscita originale: **363**
- Gruppi con originale chiuso ma Shadow ancora attive: **406**
- Confronti completati: **86313**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2594 | 2659 | €-2,66 | 44,8% | 581 | 432 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2566 | 2631 | +€8,39 | 50,2% | 790 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2566 | 2631 | +€3,90 | 46,9% | 883 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2566 | 2631 | €-2,18 | 39,5% | 329 | 649 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2552 | 2617 | +€6,70 | 48,8% | 796 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2548 | 2613 | +€4,60 | 47,8% | 801 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2544 | 2609 | +€3,05 | 47,3% | 756 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2526 | 2591 | +€7,28 | 44,7% | 636 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2526 | 2591 | +€4,75 | 42,0% | 707 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2508 | 2573 | +€5,33 | 44,3% | 609 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2508 | 2573 | +€3,73 | 44,2% | 521 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2500 | 2565 | +€1,88 | 41,9% | 444 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2474 | 2539 | +€6,01 | 33,9% | 376 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2446 | 2511 | €-1,88 | 33,5% | 302 | 544 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2433 | 2498 | +€5,71 | 38,7% | 179 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2412 | 2477 | €-5,65 | 33,4% | 163 | 745 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2394 | 2459 | €-2,87 | 31,0% | 265 | 599 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2389 | 2454 | €-8,10 | 32,4% | 466 | 492 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2355 | 2420 | €-7,26 | 29,1% | 218 | 643 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2304 | 2369 | €-14,18 | 23,1% | 217 | 746 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
