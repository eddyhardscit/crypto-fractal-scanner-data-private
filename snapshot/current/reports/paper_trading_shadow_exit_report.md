# Block 3 — Shadow Exit Engine

Generato: 2026-08-03T10:54:08+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **117**
- Scenari virtuali ancora attivi: **1521**
- Gruppi in attesa dell'uscita originale: **18**
- Gruppi con originale chiuso ma Shadow ancora attive: **99**
- Confronti completati: **119348**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3220 | 3286 | +€9,20 | 51,8% | 912 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3220 | 3286 | +€7,53 | 50,9% | 911 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3220 | 3286 | +€6,29 | 49,3% | 910 | 78 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3220 | 3286 | +€4,89 | 48,8% | 1013 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3217 | 3283 | €-1,12 | 39,5% | 399 | 732 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3217 | 3283 | €-1,48 | 45,7% | 668 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3214 | 3280 | +€6,73 | 43,3% | 706 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3214 | 3280 | +€4,86 | 42,8% | 682 | 126 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3214 | 3280 | +€4,65 | 49,3% | 852 | 136 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3214 | 3280 | +€4,53 | 41,2% | 774 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3214 | 3280 | +€4,20 | 41,9% | 597 | 215 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3213 | 3279 | +€5,12 | 33,2% | 411 | 380 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3208 | 3274 | +€3,84 | 35,7% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3208 | 3274 | +€2,29 | 40,2% | 514 | 369 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3208 | 3274 | €-4,63 | 31,7% | 187 | 992 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3205 | 3271 | €-0,33 | 31,6% | 367 | 682 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3205 | 3271 | €-1,02 | 29,0% | 311 | 813 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3195 | 3261 | €-5,70 | 27,3% | 260 | 891 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3143 | 3209 | €-4,49 | 32,7% | 547 | 675 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3142 | 3208 | €-9,60 | 21,9% | 260 | 1005 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
