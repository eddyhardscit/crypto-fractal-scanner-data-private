# Block 3 — Shadow Exit Engine

Generato: 2026-08-09T02:54:00+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **12**
- Scenari virtuali ancora attivi: **120**
- Gruppi in attesa dell'uscita originale: **6**
- Gruppi con originale chiuso ma Shadow ancora attive: **6**
- Confronti completati: **123726**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3288 | 3354 | +€9,07 | 51,6% | 925 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3288 | 3354 | +€7,44 | 50,6% | 925 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3288 | 3354 | +€6,66 | 43,2% | 711 | 90 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3288 | 3354 | +€5,08 | 33,2% | 412 | 383 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3288 | 3354 | +€4,84 | 48,5% | 1028 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3288 | 3354 | +€4,83 | 42,8% | 687 | 128 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3288 | 3354 | +€4,52 | 41,2% | 779 | 88 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3288 | 3354 | +€3,79 | 35,7% | 199 | 624 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3288 | 3354 | €-1,40 | 45,5% | 671 | 502 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3285 | 3351 | +€6,21 | 49,0% | 926 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3285 | 3351 | +€4,60 | 48,9% | 868 | 140 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3285 | 3351 | +€4,17 | 41,7% | 604 | 217 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3285 | 3351 | +€2,30 | 39,9% | 520 | 377 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3285 | 3351 | €-0,31 | 31,4% | 369 | 699 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3285 | 3351 | €-3,71 | 32,8% | 557 | 715 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3282 | 3348 | €-0,99 | 28,7% | 312 | 835 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3282 | 3348 | €-1,03 | 39,6% | 401 | 737 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3282 | 3348 | €-4,47 | 31,8% | 188 | 1003 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3282 | 3348 | €-5,30 | 27,2% | 261 | 912 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3282 | 3348 | €-8,59 | 22,6% | 261 | 1045 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
