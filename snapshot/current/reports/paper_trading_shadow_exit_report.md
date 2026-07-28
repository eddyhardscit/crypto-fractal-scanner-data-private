# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T10:38:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **738**
- Scenari virtuali ancora attivi: **16205**
- Gruppi in attesa dell'uscita originale: **352**
- Gruppi con originale chiuso ma Shadow ancora attive: **386**
- Confronti completati: **84703**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2557 | 2622 | €-2,78 | 44,6% | 573 | 431 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2531 | 2596 | +€8,27 | 50,1% | 783 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2531 | 2596 | +€3,69 | 46,8% | 875 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2518 | 2583 | +€6,55 | 48,7% | 789 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2514 | 2579 | +€4,44 | 47,7% | 794 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2512 | 2577 | +€2,89 | 47,2% | 751 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2510 | 2575 | €-2,42 | 39,0% | 322 | 644 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2494 | 2559 | +€7,21 | 44,6% | 629 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2494 | 2559 | +€4,66 | 41,9% | 700 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2477 | 2542 | +€5,24 | 44,2% | 603 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2477 | 2542 | +€3,66 | 44,0% | 515 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2471 | 2536 | +€1,81 | 41,7% | 440 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2442 | 2507 | +€5,82 | 33,7% | 369 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2412 | 2477 | €-1,94 | 33,3% | 298 | 544 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2399 | 2464 | +€5,67 | 38,4% | 178 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2397 | 2462 | €-5,69 | 33,3% | 163 | 745 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2361 | 2426 | €-8,32 | 32,1% | 462 | 492 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2360 | 2425 | €-2,95 | 30,8% | 261 | 599 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2321 | 2386 | €-7,40 | 28,8% | 214 | 643 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2270 | 2335 | €-14,43 | 22,7% | 213 | 746 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
