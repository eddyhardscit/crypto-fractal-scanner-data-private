# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T02:38:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **657**
- Scenari virtuali ancora attivi: **13528**
- Gruppi in attesa dell'uscita originale: **374**
- Gruppi con originale chiuso ma Shadow ancora attive: **283**
- Confronti completati: **80613**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2408 | 2473 | +€8,20 | 49,7% | 734 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2408 | 2473 | +€3,59 | 46,2% | 826 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2408 | 2473 | €-2,73 | 44,4% | 521 | 426 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2396 | 2461 | +€6,47 | 48,3% | 741 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2392 | 2457 | +€4,40 | 47,1% | 746 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2387 | 2452 | +€2,85 | 46,7% | 709 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2386 | 2451 | +€6,47 | 44,2% | 583 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2386 | 2451 | +€3,81 | 41,4% | 654 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2370 | 2435 | +€4,54 | 43,8% | 557 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2370 | 2435 | +€3,10 | 43,7% | 469 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2364 | 2429 | +€1,38 | 41,3% | 401 | 301 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2360 | 2425 | +€5,01 | 33,3% | 342 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2354 | 2419 | €-2,53 | 32,6% | 291 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2352 | 2417 | €-3,57 | 38,1% | 290 | 621 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2344 | 2409 | +€4,70 | 38,3% | 169 | 428 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2307 | 2372 | €-3,53 | 30,0% | 256 | 590 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2305 | 2370 | €-7,06 | 31,9% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2281 | 2346 | €-8,81 | 30,9% | 456 | 482 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2268 | 2333 | €-8,76 | 27,9% | 209 | 634 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2204 | 2269 | €-14,75 | 21,7% | 208 | 726 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
