# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T13:38:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **763**
- Scenari virtuali ancora attivi: **15961**
- Gruppi in attesa dell'uscita originale: **347**
- Gruppi con originale chiuso ma Shadow ancora attive: **416**
- Confronti completati: **87029**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2615 | 2680 | €-2,70 | 44,8% | 584 | 432 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2593 | 2658 | €-2,16 | 39,8% | 331 | 649 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2587 | 2652 | +€8,35 | 50,5% | 793 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2587 | 2652 | +€3,88 | 47,2% | 886 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2573 | 2638 | +€6,67 | 49,1% | 799 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2562 | 2627 | +€4,54 | 47,9% | 804 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2558 | 2623 | +€2,99 | 47,5% | 759 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2540 | 2605 | +€7,23 | 44,9% | 638 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2540 | 2605 | +€4,71 | 42,3% | 709 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2522 | 2587 | +€5,28 | 44,5% | 611 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2522 | 2587 | +€3,69 | 44,3% | 523 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2513 | 2578 | +€1,85 | 42,1% | 446 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2487 | 2552 | +€5,99 | 34,2% | 378 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2457 | 2522 | €-1,82 | 33,8% | 302 | 544 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2446 | 2511 | +€5,70 | 38,9% | 181 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2430 | 2495 | €-5,56 | 33,6% | 163 | 745 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2405 | 2470 | €-2,81 | 31,3% | 265 | 599 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2400 | 2465 | €-8,02 | 32,7% | 466 | 492 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2366 | 2431 | €-7,18 | 29,4% | 218 | 643 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2315 | 2380 | €-14,07 | 23,4% | 217 | 746 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
