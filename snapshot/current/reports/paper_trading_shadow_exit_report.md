# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T08:38:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **727**
- Scenari virtuali ancora attivi: **15340**
- Gruppi in attesa dell'uscita originale: **331**
- Gruppi con originale chiuso ma Shadow ancora attive: **396**
- Confronti completati: **84465**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2553 | 2618 | €-2,72 | 44,7% | 569 | 431 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2527 | 2592 | +€8,25 | 50,1% | 782 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2527 | 2592 | +€3,69 | 46,7% | 874 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2515 | 2580 | +€6,50 | 48,7% | 789 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2511 | 2576 | +€4,40 | 47,6% | 794 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2509 | 2574 | +€2,85 | 47,1% | 751 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2492 | 2557 | €-2,30 | 39,3% | 318 | 630 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2490 | 2555 | +€7,18 | 44,5% | 628 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2490 | 2555 | +€4,62 | 41,8% | 699 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2474 | 2539 | +€5,20 | 44,1% | 603 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2474 | 2539 | +€3,61 | 44,0% | 515 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2468 | 2533 | +€1,77 | 41,6% | 440 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2438 | 2503 | +€5,90 | 33,7% | 365 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2409 | 2474 | €-1,95 | 33,2% | 298 | 544 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2395 | 2460 | +€5,74 | 38,5% | 174 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2358 | 2423 | €-6,18 | 32,6% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2357 | 2422 | €-2,96 | 30,7% | 261 | 599 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2357 | 2422 | €-8,32 | 32,0% | 462 | 491 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2318 | 2383 | €-7,42 | 28,7% | 214 | 643 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2256 | 2321 | €-14,06 | 22,7% | 213 | 735 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
