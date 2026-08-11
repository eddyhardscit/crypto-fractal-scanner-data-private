# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T13:10:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **318**
- Scenari virtuali ancora attivi: **11093**
- Gruppi in attesa dell'uscita originale: **261**
- Gruppi con originale chiuso ma Shadow ancora attive: **57**
- Confronti completati: **128302**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3403 | 3469 | +€8,14 | 50,9% | 970 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3403 | 3469 | +€6,89 | 49,8% | 955 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3403 | 3469 | +€6,14 | 42,9% | 756 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3403 | 3469 | +€5,60 | 48,3% | 953 | 108 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3403 | 3469 | +€4,45 | 42,2% | 717 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3403 | 3469 | +€4,00 | 40,9% | 824 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3403 | 3469 | +€3,90 | 47,9% | 1080 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3403 | 3469 | +€3,69 | 41,3% | 631 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3394 | 3460 | €-1,29 | 45,6% | 691 | 515 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3391 | 3457 | +€4,78 | 32,9% | 440 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3385 | 3451 | +€4,19 | 48,5% | 892 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3385 | 3451 | +€1,99 | 39,8% | 544 | 390 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3382 | 3448 | +€3,80 | 35,8% | 211 | 627 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3371 | 3437 | €-0,43 | 40,2% | 404 | 740 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3347 | 3413 | €-3,56 | 33,0% | 560 | 718 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3346 | 3412 | €-0,18 | 31,7% | 370 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3346 | 3412 | €-0,85 | 29,0% | 314 | 840 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3346 | 3412 | €-4,28 | 32,0% | 191 | 1009 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3346 | 3412 | €-5,08 | 27,5% | 263 | 918 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3346 | 3412 | €-8,32 | 23,0% | 263 | 1051 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
