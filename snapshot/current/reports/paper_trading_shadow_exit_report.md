# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T03:38:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **665**
- Scenari virtuali ancora attivi: **13776**
- Gruppi in attesa dell'uscita originale: **376**
- Gruppi con originale chiuso ma Shadow ancora attive: **289**
- Confronti completati: **80955**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2420 | 2485 | €-2,86 | 44,2% | 527 | 428 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2417 | 2482 | +€8,15 | 49,6% | 740 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2417 | 2482 | +€3,52 | 46,1% | 832 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2405 | 2470 | +€6,42 | 48,1% | 747 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2401 | 2466 | +€4,34 | 47,0% | 752 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2395 | 2460 | +€6,43 | 44,0% | 589 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2395 | 2460 | +€3,79 | 41,2% | 660 | 65 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2395 | 2460 | €-2,83 | 38,9% | 290 | 626 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2390 | 2455 | +€2,84 | 46,6% | 709 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2379 | 2444 | +€4,50 | 43,6% | 563 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2379 | 2444 | +€3,05 | 43,5% | 475 | 159 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2369 | 2434 | +€5,03 | 33,4% | 342 | 269 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2367 | 2432 | +€1,37 | 41,2% | 401 | 301 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2357 | 2422 | €-2,53 | 32,6% | 291 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2348 | 2413 | +€4,71 | 38,3% | 169 | 428 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2310 | 2375 | €-3,53 | 29,9% | 256 | 590 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2308 | 2373 | €-7,05 | 31,9% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
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
