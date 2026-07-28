# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T01:23:55+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **626**
- Scenari virtuali ancora attivi: **12850**
- Gruppi in attesa dell'uscita originale: **347**
- Gruppi con originale chiuso ma Shadow ancora attive: **279**
- Confronti completati: **80485**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2404 | 2469 | +€8,20 | 49,7% | 733 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2404 | 2469 | +€3,61 | 46,3% | 822 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2392 | 2457 | +€6,48 | 48,2% | 740 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2392 | 2457 | €-2,77 | 44,5% | 521 | 421 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2388 | 2453 | +€4,40 | 47,2% | 745 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2383 | 2448 | +€2,86 | 46,8% | 705 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2382 | 2447 | +€6,47 | 44,1% | 582 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2382 | 2447 | +€3,81 | 41,3% | 653 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2366 | 2431 | +€4,54 | 43,7% | 556 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2366 | 2431 | +€3,11 | 43,8% | 468 | 159 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2359 | 2424 | +€5,01 | 33,3% | 341 | 269 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2359 | 2424 | +€1,39 | 41,3% | 397 | 300 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2354 | 2419 | €-2,53 | 32,6% | 291 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2343 | 2408 | +€4,70 | 38,2% | 169 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2342 | 2407 | €-3,64 | 38,1% | 290 | 616 | READY_FOR_BLOCK4_EVALUATION |
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
