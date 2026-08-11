# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T11:11:10+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **306**
- Scenari virtuali ancora attivi: **11155**
- Gruppi in attesa dell'uscita originale: **272**
- Gruppi con originale chiuso ma Shadow ancora attive: **34**
- Confronti completati: **126828**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3363 | 3429 | +€8,37 | 51,2% | 959 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3363 | 3429 | +€7,11 | 50,3% | 937 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3363 | 3429 | +€6,30 | 43,0% | 745 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3363 | 3429 | +€5,85 | 48,7% | 935 | 108 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3363 | 3429 | +€4,85 | 33,2% | 438 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3363 | 3429 | +€4,62 | 42,6% | 699 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3363 | 3429 | +€4,16 | 48,3% | 1062 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3363 | 3429 | +€4,09 | 41,1% | 813 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3363 | 3429 | +€3,87 | 41,6% | 613 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3363 | 3429 | +€3,84 | 36,0% | 209 | 627 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3363 | 3429 | €-1,28 | 45,9% | 682 | 515 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3345 | 3411 | +€4,44 | 48,9% | 874 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3345 | 3411 | +€2,20 | 40,1% | 526 | 390 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3330 | 3396 | €-3,58 | 33,2% | 560 | 718 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3329 | 3395 | €-0,18 | 31,8% | 370 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3329 | 3395 | €-0,86 | 29,1% | 314 | 840 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3329 | 3395 | €-0,90 | 39,9% | 404 | 740 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3329 | 3395 | €-4,30 | 32,2% | 191 | 1009 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3329 | 3395 | €-5,11 | 27,7% | 263 | 918 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3329 | 3395 | €-8,36 | 23,1% | 263 | 1051 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
