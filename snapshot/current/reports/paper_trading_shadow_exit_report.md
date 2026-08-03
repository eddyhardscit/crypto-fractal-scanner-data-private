# Block 3 — Shadow Exit Engine

Generato: 2026-08-03T08:39:03+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **111**
- Scenari virtuali ancora attivi: **1374**
- Gruppi in attesa dell'uscita originale: **17**
- Gruppi con originale chiuso ma Shadow ancora attive: **94**
- Confronti completati: **119216**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3217 | 3283 | €-1,48 | 45,7% | 668 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3215 | 3281 | +€9,22 | 51,9% | 907 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3215 | 3281 | +€7,55 | 50,9% | 911 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3215 | 3281 | +€6,30 | 49,4% | 910 | 73 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3215 | 3281 | +€4,91 | 48,9% | 1008 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3214 | 3280 | €-1,14 | 39,5% | 399 | 732 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3211 | 3277 | +€4,65 | 49,3% | 852 | 133 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3209 | 3275 | +€6,74 | 43,3% | 703 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3209 | 3275 | +€4,87 | 42,9% | 682 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3209 | 3275 | +€4,54 | 41,3% | 769 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3209 | 3275 | +€4,21 | 41,9% | 597 | 210 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3208 | 3274 | +€5,13 | 33,2% | 410 | 380 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3208 | 3274 | €-4,63 | 31,7% | 187 | 992 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3205 | 3271 | +€3,85 | 35,6% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3205 | 3271 | +€2,29 | 40,2% | 514 | 366 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3205 | 3271 | €-0,33 | 31,6% | 367 | 682 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3202 | 3268 | €-1,04 | 29,0% | 311 | 813 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3192 | 3258 | €-5,72 | 27,2% | 260 | 891 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3143 | 3209 | €-4,49 | 32,7% | 547 | 675 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3142 | 3208 | €-9,60 | 21,9% | 260 | 1005 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
