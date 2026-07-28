# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T07:38:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **716**
- Scenari virtuali ancora attivi: **15727**
- Gruppi in attesa dell'uscita originale: **362**
- Gruppi con originale chiuso ma Shadow ancora attive: **354**
- Confronti completati: **83154**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2515 | 2580 | €-2,80 | 44,1% | 562 | 431 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2484 | 2549 | +€8,09 | 49,5% | 775 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2484 | 2549 | +€3,46 | 46,1% | 867 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2472 | 2537 | +€6,36 | 48,1% | 782 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2468 | 2533 | +€4,25 | 47,0% | 787 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2468 | 2533 | €-2,31 | 39,4% | 300 | 630 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2466 | 2531 | +€2,74 | 46,5% | 744 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2461 | 2526 | +€4,24 | 41,4% | 692 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2456 | 2521 | +€6,73 | 44,1% | 621 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2440 | 2505 | +€4,80 | 43,6% | 596 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2440 | 2505 | +€3,28 | 43,5% | 508 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2434 | 2499 | +€1,50 | 41,1% | 433 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2421 | 2486 | +€5,69 | 33,5% | 358 | 269 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2388 | 2453 | +€5,75 | 38,6% | 174 | 428 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2387 | 2452 | €-1,93 | 32,7% | 294 | 544 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2344 | 2409 | €-6,27 | 32,2% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2335 | 2400 | €-2,95 | 30,2% | 257 | 599 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2317 | 2382 | €-8,45 | 31,1% | 458 | 491 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2296 | 2361 | €-7,45 | 28,2% | 210 | 643 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2233 | 2298 | €-14,18 | 22,1% | 209 | 735 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
