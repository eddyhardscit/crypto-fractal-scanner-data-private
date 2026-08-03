# Block 3 — Shadow Exit Engine

Generato: 2026-08-03T14:54:07+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **117**
- Scenari virtuali ancora attivi: **1593**
- Gruppi in attesa dell'uscita originale: **20**
- Gruppi con originale chiuso ma Shadow ancora attive: **97**
- Confronti completati: **119597**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3221 | 3287 | +€9,19 | 51,8% | 912 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3221 | 3287 | +€7,53 | 50,9% | 911 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3221 | 3287 | +€6,28 | 49,3% | 910 | 78 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3221 | 3287 | +€4,89 | 48,8% | 1014 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3220 | 3286 | +€4,65 | 49,3% | 853 | 138 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3217 | 3283 | €-1,12 | 39,5% | 399 | 732 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3217 | 3283 | €-1,48 | 45,7% | 668 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3215 | 3281 | +€6,73 | 43,3% | 706 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3215 | 3281 | +€4,86 | 42,9% | 682 | 126 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3215 | 3281 | +€4,53 | 41,3% | 774 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3215 | 3281 | +€4,20 | 41,9% | 597 | 215 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3214 | 3280 | +€5,13 | 33,2% | 411 | 380 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3214 | 3280 | +€2,29 | 40,2% | 515 | 371 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3214 | 3280 | €-4,60 | 31,8% | 187 | 992 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3211 | 3277 | +€3,84 | 35,7% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3211 | 3277 | €-0,34 | 31,6% | 368 | 687 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3211 | 3277 | €-1,02 | 29,0% | 311 | 819 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3201 | 3267 | €-5,70 | 27,2% | 260 | 897 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3155 | 3221 | €-4,47 | 32,7% | 547 | 681 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3154 | 3220 | €-9,55 | 22,0% | 260 | 1011 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
