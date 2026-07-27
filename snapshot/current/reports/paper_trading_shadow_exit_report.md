# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T23:23:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **637**
- Scenari virtuali ancora attivi: **11732**
- Gruppi in attesa dell'uscita originale: **354**
- Gruppi con originale chiuso ma Shadow ancora attive: **283**
- Confronti completati: **78569**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2350 | 2415 | €-3,26 | 44,3% | 507 | 420 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2349 | 2414 | +€7,58 | 49,7% | 710 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2349 | 2414 | +€5,72 | 48,0% | 728 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2349 | 2414 | +€2,99 | 46,2% | 798 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2347 | 2412 | +€3,57 | 46,9% | 735 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2346 | 2411 | +€2,01 | 46,4% | 699 | 90 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2331 | 2396 | +€2,96 | 41,2% | 631 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2329 | 2394 | +€5,56 | 44,1% | 558 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2329 | 2394 | +€3,56 | 43,4% | 548 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2329 | 2394 | +€2,17 | 43,5% | 460 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2327 | 2392 | +€0,46 | 41,0% | 392 | 300 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2326 | 2391 | €-3,21 | 32,1% | 289 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2309 | 2374 | +€3,97 | 33,0% | 321 | 269 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2297 | 2362 | €-3,85 | 37,9% | 290 | 605 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2283 | 2348 | +€4,69 | 38,2% | 165 | 417 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2281 | 2346 | €-4,24 | 29,4% | 256 | 590 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2259 | 2324 | €-7,39 | 31,7% | 160 | 728 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2251 | 2316 | €-9,63 | 30,4% | 456 | 482 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2242 | 2307 | €-9,54 | 27,4% | 209 | 634 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2178 | 2243 | €-15,62 | 21,0% | 208 | 726 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
