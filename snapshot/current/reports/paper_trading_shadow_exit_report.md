# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T11:38:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **756**
- Scenari virtuali ancora attivi: **16403**
- Gruppi in attesa dell'uscita originale: **363**
- Gruppi con originale chiuso ma Shadow ancora attive: **393**
- Confronti completati: **85006**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2569 | 2634 | €-2,75 | 44,6% | 580 | 431 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2539 | 2604 | +€8,18 | 50,0% | 790 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2539 | 2604 | +€3,61 | 46,6% | 882 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2536 | 2601 | €-2,29 | 39,2% | 329 | 646 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2525 | 2590 | +€6,50 | 48,6% | 795 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2521 | 2586 | +€4,39 | 47,5% | 800 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2517 | 2582 | +€2,85 | 47,1% | 755 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2502 | 2567 | +€7,15 | 44,4% | 636 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2502 | 2567 | +€4,60 | 41,8% | 707 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2484 | 2549 | +€5,20 | 44,1% | 609 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2484 | 2549 | +€3,61 | 43,9% | 521 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2476 | 2541 | +€1,77 | 41,6% | 444 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2450 | 2515 | +€5,78 | 33,6% | 376 | 269 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2419 | 2484 | +€5,73 | 38,6% | 179 | 428 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2413 | 2478 | €-1,94 | 33,3% | 298 | 544 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2398 | 2463 | €-5,69 | 33,3% | 163 | 745 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2362 | 2427 | €-8,32 | 32,1% | 462 | 492 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2361 | 2426 | €-2,95 | 30,8% | 261 | 599 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2322 | 2387 | €-7,40 | 28,8% | 214 | 643 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2271 | 2336 | €-14,42 | 22,7% | 213 | 746 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
