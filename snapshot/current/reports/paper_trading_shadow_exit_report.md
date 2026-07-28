# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T05:38:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **671**
- Scenari virtuali ancora attivi: **14097**
- Gruppi in attesa dell'uscita originale: **360**
- Gruppi con originale chiuso ma Shadow ancora attive: **311**
- Confronti completati: **81742**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2460 | 2525 | €-2,28 | 44,7% | 530 | 431 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2448 | 2513 | +€8,84 | 50,1% | 743 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2448 | 2513 | +€4,18 | 46,6% | 835 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2436 | 2501 | +€7,11 | 48,6% | 750 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2432 | 2497 | +€5,01 | 47,5% | 755 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2421 | 2486 | +€7,30 | 44,6% | 589 | 67 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2421 | 2486 | +€4,63 | 41,8% | 660 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2421 | 2486 | +€3,49 | 47,2% | 712 | 90 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2421 | 2486 | €-2,29 | 39,3% | 290 | 626 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2405 | 2470 | +€5,39 | 44,1% | 565 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2405 | 2470 | +€3,91 | 44,0% | 477 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2393 | 2458 | +€2,18 | 41,7% | 403 | 302 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2382 | 2447 | +€5,91 | 33,8% | 342 | 269 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2370 | 2435 | €-1,83 | 32,9% | 291 | 532 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2361 | 2426 | +€5,72 | 38,6% | 169 | 428 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2326 | 2391 | €-6,39 | 32,2% | 160 | 739 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2323 | 2388 | €-2,92 | 30,3% | 256 | 590 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2302 | 2367 | €-8,42 | 31,2% | 456 | 482 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2284 | 2349 | €-7,44 | 28,3% | 209 | 634 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2220 | 2285 | €-14,31 | 22,1% | 208 | 726 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
