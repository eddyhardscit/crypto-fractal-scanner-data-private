# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T06:39:14+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **710**
- Scenari virtuali ancora attivi: **15800**
- Gruppi in attesa dell'uscita originale: **364**
- Gruppi con originale chiuso ma Shadow ancora attive: **346**
- Confronti completati: **82702**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2496 | 2561 | €-2,82 | 44,1% | 560 | 431 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2479 | 2544 | +€8,09 | 49,5% | 773 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2479 | 2544 | +€3,46 | 46,1% | 865 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2467 | 2532 | +€6,36 | 48,1% | 780 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2463 | 2528 | +€4,25 | 47,0% | 785 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2452 | 2517 | +€6,73 | 44,1% | 619 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2452 | 2517 | +€4,14 | 41,4% | 690 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2452 | 2517 | +€2,78 | 46,6% | 742 | 90 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2437 | 2502 | €-2,34 | 39,1% | 300 | 626 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2436 | 2501 | +€4,80 | 43,6% | 595 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2436 | 2501 | +€3,28 | 43,5% | 507 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2423 | 2488 | +€1,53 | 41,2% | 432 | 302 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2418 | 2483 | +€5,69 | 33,5% | 358 | 269 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2387 | 2452 | +€5,75 | 38,6% | 174 | 428 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2373 | 2438 | €-1,89 | 32,9% | 293 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2332 | 2397 | €-6,37 | 32,2% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2324 | 2389 | €-2,91 | 30,3% | 256 | 590 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2304 | 2369 | €-8,44 | 31,2% | 457 | 482 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2285 | 2350 | €-7,43 | 28,3% | 209 | 634 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2221 | 2286 | €-14,30 | 22,2% | 208 | 726 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
