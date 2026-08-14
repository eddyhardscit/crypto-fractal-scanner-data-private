# Block 3 — Shadow Exit Engine

Generato: 2026-08-14T05:06:55+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **591**
- Scenari virtuali ancora attivi: **10705**
- Gruppi in attesa dell'uscita originale: **364**
- Gruppi con originale chiuso ma Shadow ancora attive: **227**
- Confronti completati: **186581**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4577 | 4643 | +€8,13 | 51,0% | 1199 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4577 | 4643 | +€7,15 | 50,0% | 1191 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4577 | 4643 | +€4,40 | 48,1% | 1337 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4576 | 4642 | +€5,84 | 48,2% | 1205 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4575 | 4641 | +€4,48 | 48,5% | 1133 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4572 | 4638 | €-0,50 | 46,5% | 852 | 666 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4572 | 4638 | €-0,70 | 40,8% | 484 | 957 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4571 | 4637 | €-4,77 | 32,5% | 209 | 1329 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4569 | 4635 | +€6,88 | 43,7% | 931 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4569 | 4635 | +€5,35 | 43,0% | 896 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4569 | 4635 | +€4,68 | 41,5% | 1039 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4562 | 4628 | +€5,57 | 33,8% | 558 | 454 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4561 | 4627 | +€4,50 | 42,1% | 794 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4561 | 4627 | +€2,72 | 40,9% | 672 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4553 | 4619 | +€5,58 | 37,4% | 261 | 713 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4546 | 4612 | +€1,07 | 34,6% | 481 | 833 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4543 | 4609 | +€0,17 | 32,5% | 347 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4527 | 4593 | €-4,41 | 29,2% | 294 | 1205 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4475 | 4541 | €-3,85 | 33,9% | 672 | 938 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4438 | 4504 | €-8,58 | 24,5% | 288 | 1340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
