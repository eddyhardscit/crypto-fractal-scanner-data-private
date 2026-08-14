# Block 3 — Shadow Exit Engine

Generato: 2026-08-14T04:08:03+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **579**
- Scenari virtuali ancora attivi: **11141**
- Gruppi in attesa dell'uscita originale: **353**
- Gruppi con originale chiuso ma Shadow ancora attive: **226**
- Confronti completati: **186544**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4576 | 4642 | +€8,14 | 51,0% | 1198 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4576 | 4642 | +€7,16 | 50,0% | 1190 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4576 | 4642 | +€4,41 | 48,1% | 1336 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4575 | 4641 | +€5,86 | 48,2% | 1204 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4574 | 4640 | +€4,50 | 48,6% | 1132 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4572 | 4638 | €-0,50 | 46,5% | 852 | 666 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4572 | 4638 | €-0,70 | 40,8% | 484 | 957 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4568 | 4634 | +€6,89 | 43,7% | 930 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4568 | 4634 | +€5,36 | 43,0% | 895 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4568 | 4634 | +€4,69 | 41,5% | 1038 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4566 | 4632 | €-4,91 | 32,4% | 209 | 1329 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4561 | 4627 | +€5,58 | 33,8% | 557 | 454 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4560 | 4626 | +€4,52 | 42,1% | 793 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4560 | 4626 | +€2,74 | 40,9% | 671 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4548 | 4614 | +€5,57 | 37,4% | 261 | 713 | READY_FOR_BLOCK4_EVALUATION |
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
