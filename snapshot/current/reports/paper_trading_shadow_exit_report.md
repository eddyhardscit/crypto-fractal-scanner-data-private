# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T14:38:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **787**
- Scenari virtuali ancora attivi: **15435**
- Gruppi in attesa dell'uscita originale: **346**
- Gruppi con originale chiuso ma Shadow ancora attive: **441**
- Confronti completati: **88129**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2633 | 2698 | €-2,83 | 44,6% | 598 | 432 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2628 | 2693 | €-2,19 | 39,4% | 345 | 666 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2622 | 2687 | +€8,18 | 50,5% | 807 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2622 | 2687 | +€3,70 | 47,2% | 900 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2606 | 2671 | +€6,57 | 49,2% | 811 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2595 | 2660 | +€4,44 | 48,0% | 816 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2591 | 2656 | +€2,90 | 47,5% | 771 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2566 | 2631 | +€7,10 | 44,8% | 652 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2566 | 2631 | +€4,61 | 42,2% | 723 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2546 | 2611 | +€5,21 | 44,4% | 623 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2546 | 2611 | +€3,62 | 44,2% | 535 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2537 | 2602 | +€1,77 | 42,0% | 458 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2507 | 2572 | +€5,90 | 34,0% | 388 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2465 | 2530 | €-1,82 | 33,7% | 302 | 544 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2461 | 2526 | +€5,64 | 38,7% | 184 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2444 | 2509 | €-5,48 | 33,6% | 163 | 750 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2419 | 2484 | €-7,96 | 32,7% | 466 | 492 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2413 | 2478 | €-2,80 | 31,2% | 265 | 599 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2374 | 2439 | €-7,15 | 29,3% | 218 | 643 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2323 | 2388 | €-14,02 | 23,4% | 217 | 746 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
