# Block 3 — Shadow Exit Engine

Generato: 2026-08-03T22:54:19+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **41**
- Scenari virtuali ancora attivi: **603**
- Gruppi in attesa dell'uscita originale: **15**
- Gruppi con originale chiuso ma Shadow ancora attive: **26**
- Confronti completati: **120789**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3234 | 3300 | €-1,45 | 45,8% | 669 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3232 | 3298 | +€9,17 | 51,9% | 912 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3232 | 3298 | +€7,51 | 50,9% | 912 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3232 | 3298 | +€6,27 | 49,4% | 911 | 78 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3232 | 3298 | +€4,88 | 48,8% | 1015 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3232 | 3298 | +€4,63 | 49,3% | 854 | 138 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3231 | 3297 | €-1,09 | 39,6% | 399 | 732 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3226 | 3292 | +€6,72 | 43,4% | 706 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3226 | 3292 | +€4,85 | 43,0% | 682 | 126 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3226 | 3292 | +€4,52 | 41,4% | 774 | 86 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3225 | 3291 | +€5,12 | 33,3% | 411 | 380 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3225 | 3291 | €-4,58 | 31,9% | 187 | 992 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3223 | 3289 | +€4,19 | 41,9% | 597 | 215 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3223 | 3289 | +€2,29 | 40,2% | 515 | 371 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3223 | 3289 | €-0,34 | 31,5% | 368 | 690 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3223 | 3289 | €-1,02 | 29,0% | 311 | 822 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3220 | 3286 | +€3,84 | 35,7% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3217 | 3283 | €-4,16 | 33,2% | 547 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3217 | 3283 | €-5,78 | 27,2% | 260 | 904 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3217 | 3283 | €-9,15 | 22,6% | 260 | 1032 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
