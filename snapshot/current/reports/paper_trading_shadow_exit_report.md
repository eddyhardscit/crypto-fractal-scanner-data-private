# Block 3 — Shadow Exit Engine

Generato: 2026-08-03T07:39:54+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **114**
- Scenari virtuali ancora attivi: **1524**
- Gruppi in attesa dell'uscita originale: **20**
- Gruppi con originale chiuso ma Shadow ancora attive: **94**
- Confronti completati: **119066**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3214 | 3280 | €-1,48 | 45,7% | 668 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3212 | 3278 | +€9,22 | 51,9% | 907 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3212 | 3278 | +€7,55 | 51,0% | 911 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3212 | 3278 | +€6,30 | 49,4% | 910 | 73 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3212 | 3278 | +€4,91 | 48,9% | 1008 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3211 | 3277 | €-1,14 | 39,5% | 399 | 732 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3208 | 3274 | +€4,66 | 49,4% | 852 | 133 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3206 | 3272 | +€6,75 | 43,3% | 703 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3206 | 3272 | +€4,88 | 42,9% | 682 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3206 | 3272 | +€4,54 | 41,4% | 769 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3206 | 3272 | +€4,21 | 42,0% | 597 | 210 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3205 | 3271 | +€5,14 | 33,2% | 410 | 380 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3205 | 3271 | €-4,64 | 31,7% | 187 | 992 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3202 | 3268 | +€3,85 | 35,7% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3202 | 3268 | +€2,30 | 40,3% | 514 | 366 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3202 | 3268 | €-0,33 | 31,6% | 367 | 682 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3199 | 3265 | €-1,04 | 29,0% | 311 | 813 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3189 | 3255 | €-5,73 | 27,3% | 260 | 891 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3140 | 3206 | €-4,49 | 32,7% | 547 | 675 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3139 | 3205 | €-9,61 | 21,9% | 260 | 1005 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
