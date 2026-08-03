# Block 3 — Shadow Exit Engine

Generato: 2026-08-03T21:54:12+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **51**
- Scenari virtuali ancora attivi: **776**
- Gruppi in attesa dell'uscita originale: **17**
- Gruppi con originale chiuso ma Shadow ancora attive: **34**
- Confronti completati: **120564**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3232 | 3298 | €-1,45 | 45,8% | 669 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3230 | 3296 | +€9,17 | 51,9% | 912 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3230 | 3296 | +€7,51 | 50,9% | 912 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3230 | 3296 | +€6,27 | 49,3% | 911 | 78 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3230 | 3296 | +€4,88 | 48,8% | 1015 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3229 | 3295 | +€4,64 | 49,3% | 854 | 138 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3229 | 3295 | €-1,09 | 39,7% | 399 | 732 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3224 | 3290 | +€4,52 | 41,3% | 774 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3221 | 3287 | +€6,72 | 43,3% | 706 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3221 | 3287 | +€4,86 | 42,9% | 682 | 126 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3221 | 3287 | +€4,19 | 41,9% | 597 | 215 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3220 | 3286 | +€5,12 | 33,2% | 411 | 380 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3220 | 3286 | +€2,29 | 40,2% | 515 | 371 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3220 | 3286 | €-0,34 | 31,6% | 368 | 690 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3220 | 3286 | €-1,02 | 29,0% | 311 | 822 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3220 | 3286 | €-4,59 | 31,8% | 187 | 992 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3217 | 3283 | +€3,84 | 35,8% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3210 | 3276 | €-5,69 | 27,3% | 260 | 900 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3207 | 3273 | €-4,09 | 33,2% | 547 | 698 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3207 | 3273 | €-9,09 | 22,6% | 260 | 1028 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
