# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T00:23:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **610**
- Scenari virtuali ancora attivi: **11806**
- Gruppi in attesa dell'uscita originale: **343**
- Gruppi con originale chiuso ma Shadow ancora attive: **267**
- Confronti completati: **79821**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2381 | 2446 | €-2,66 | 44,6% | 515 | 421 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2379 | 2444 | +€8,47 | 50,1% | 714 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2379 | 2444 | +€6,59 | 48,4% | 732 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2379 | 2444 | +€3,84 | 46,7% | 802 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2377 | 2442 | +€4,42 | 47,4% | 739 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2375 | 2440 | +€2,84 | 46,9% | 702 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2357 | 2422 | +€6,58 | 44,5% | 563 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2357 | 2422 | +€3,95 | 41,7% | 634 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2355 | 2420 | +€4,55 | 43,8% | 551 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2355 | 2420 | +€3,12 | 43,9% | 463 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2352 | 2417 | +€1,36 | 41,4% | 395 | 300 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2349 | 2414 | €-2,56 | 32,6% | 291 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2335 | 2400 | €-3,68 | 38,1% | 290 | 616 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2334 | 2399 | +€5,14 | 33,6% | 323 | 269 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2317 | 2382 | +€4,75 | 38,5% | 167 | 428 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2302 | 2367 | €-3,56 | 30,0% | 256 | 590 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2298 | 2363 | €-7,08 | 32,0% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2276 | 2341 | €-8,85 | 31,0% | 456 | 482 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2263 | 2328 | €-8,80 | 28,0% | 209 | 634 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2199 | 2264 | €-14,80 | 21,7% | 208 | 726 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
