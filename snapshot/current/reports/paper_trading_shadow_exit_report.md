# Block 3 — Shadow Exit Engine

Generato: 2026-08-14T03:06:55+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **558**
- Scenari virtuali ancora attivi: **9818**
- Gruppi in attesa dell'uscita originale: **348**
- Gruppi con originale chiuso ma Shadow ancora attive: **210**
- Confronti completati: **185091**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4545 | 4611 | +€8,05 | 50,7% | 1198 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4545 | 4611 | +€7,08 | 49,7% | 1190 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4545 | 4611 | +€4,30 | 47,8% | 1336 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4544 | 4610 | +€5,76 | 48,0% | 1204 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4543 | 4609 | +€4,41 | 48,3% | 1132 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4541 | 4607 | €-0,61 | 46,2% | 849 | 666 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4541 | 4607 | €-0,88 | 40,5% | 484 | 957 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4537 | 4603 | +€6,72 | 43,4% | 930 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4537 | 4603 | +€5,20 | 42,7% | 895 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4537 | 4603 | +€4,50 | 41,2% | 1038 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4530 | 4596 | +€5,31 | 33,5% | 557 | 454 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4529 | 4595 | +€4,36 | 41,8% | 793 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4529 | 4595 | +€2,59 | 40,6% | 671 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4528 | 4594 | €-5,13 | 32,2% | 209 | 1322 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4517 | 4583 | +€5,36 | 37,2% | 261 | 713 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4515 | 4581 | +€0,90 | 34,3% | 481 | 833 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4512 | 4578 | €-0,02 | 32,1% | 347 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4456 | 4522 | €-3,94 | 33,8% | 671 | 937 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4456 | 4522 | €-4,72 | 28,6% | 288 | 1193 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4420 | 4486 | €-8,69 | 24,3% | 288 | 1339 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
