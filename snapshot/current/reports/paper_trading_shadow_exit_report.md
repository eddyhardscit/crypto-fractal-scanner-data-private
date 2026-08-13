# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T22:08:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **593**
- Scenari virtuali ancora attivi: **11670**
- Gruppi in attesa dell'uscita originale: **383**
- Gruppi con originale chiuso ma Shadow ancora attive: **210**
- Confronti completati: **182096**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4480 | 4546 | +€8,04 | 50,3% | 1185 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4480 | 4546 | +€7,05 | 49,3% | 1177 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4480 | 4546 | +€6,63 | 42,8% | 924 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4480 | 4546 | +€5,11 | 42,1% | 889 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4480 | 4546 | +€4,37 | 40,6% | 1032 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4480 | 4546 | +€4,24 | 47,4% | 1323 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4479 | 4545 | +€5,74 | 47,5% | 1191 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4478 | 4544 | +€4,39 | 47,8% | 1119 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4473 | 4539 | +€5,26 | 33,1% | 557 | 447 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4472 | 4538 | +€4,29 | 41,3% | 781 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4472 | 4538 | +€2,53 | 40,2% | 658 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4470 | 4536 | €-0,37 | 46,0% | 846 | 649 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4470 | 4536 | €-0,69 | 40,2% | 482 | 940 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4464 | 4530 | +€5,25 | 36,8% | 261 | 706 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4461 | 4527 | +€0,79 | 33,6% | 478 | 833 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4453 | 4519 | €-0,19 | 31,4% | 345 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4445 | 4511 | €-5,01 | 32,0% | 209 | 1292 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4412 | 4478 | €-4,91 | 28,1% | 288 | 1193 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4399 | 4465 | €-4,05 | 33,5% | 662 | 934 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4380 | 4446 | €-8,86 | 23,9% | 288 | 1336 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
