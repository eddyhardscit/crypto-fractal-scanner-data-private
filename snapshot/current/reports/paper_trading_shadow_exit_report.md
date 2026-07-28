# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T04:38:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **679**
- Scenari virtuali ancora attivi: **14394**
- Gruppi in attesa dell'uscita originale: **376**
- Gruppi con originale chiuso ma Shadow ancora attive: **303**
- Confronti completati: **81224**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2429 | 2494 | €-2,87 | 44,1% | 530 | 428 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2427 | 2492 | +€8,24 | 49,6% | 743 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2427 | 2492 | +€3,55 | 46,1% | 835 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2415 | 2480 | +€6,50 | 48,2% | 750 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2411 | 2476 | +€4,41 | 47,1% | 755 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2406 | 2471 | €-2,81 | 39,0% | 290 | 626 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2405 | 2470 | +€6,53 | 44,3% | 589 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2405 | 2470 | +€3,90 | 41,5% | 660 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2400 | 2465 | +€2,90 | 46,7% | 712 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2389 | 2454 | +€4,59 | 43,8% | 565 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2389 | 2454 | +€3,13 | 43,6% | 477 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2376 | 2441 | +€1,43 | 41,3% | 403 | 301 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2369 | 2434 | +€5,03 | 33,4% | 342 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2357 | 2422 | €-2,53 | 32,6% | 291 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2348 | 2413 | +€4,71 | 38,3% | 169 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2312 | 2377 | €-7,04 | 31,8% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2310 | 2375 | €-3,53 | 29,9% | 256 | 590 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2284 | 2349 | €-8,80 | 30,9% | 456 | 482 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2271 | 2336 | €-8,75 | 27,9% | 209 | 634 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2207 | 2272 | €-14,73 | 21,7% | 208 | 726 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
