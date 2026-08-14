# Block 3 — Shadow Exit Engine

Generato: 2026-08-14T01:07:29+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **576**
- Scenari virtuali ancora attivi: **10504**
- Gruppi in attesa dell'uscita originale: **379**
- Gruppi con originale chiuso ma Shadow ancora attive: **197**
- Confronti completati: **182883**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4497 | 4563 | +€8,06 | 50,5% | 1185 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4497 | 4563 | +€7,07 | 49,5% | 1177 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4497 | 4563 | +€4,28 | 47,6% | 1323 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4496 | 4562 | +€5,76 | 47,7% | 1191 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4495 | 4561 | +€4,41 | 48,0% | 1119 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4490 | 4556 | €-0,63 | 46,0% | 846 | 659 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4490 | 4556 | €-0,96 | 40,2% | 482 | 950 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4489 | 4555 | +€6,63 | 42,9% | 924 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4489 | 4555 | +€5,11 | 42,2% | 889 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4489 | 4555 | +€4,38 | 40,7% | 1032 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4481 | 4547 | +€4,29 | 41,4% | 781 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4481 | 4547 | +€2,53 | 40,3% | 658 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4479 | 4545 | €-5,28 | 31,8% | 209 | 1315 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4475 | 4541 | +€5,26 | 33,1% | 557 | 447 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4470 | 4536 | +€0,79 | 33,7% | 478 | 833 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4466 | 4532 | +€5,25 | 36,8% | 261 | 706 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4462 | 4528 | €-0,19 | 31,4% | 345 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4421 | 4487 | €-4,90 | 28,1% | 288 | 1193 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4419 | 4485 | €-4,04 | 33,4% | 662 | 937 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4392 | 4458 | €-8,84 | 23,8% | 288 | 1339 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
