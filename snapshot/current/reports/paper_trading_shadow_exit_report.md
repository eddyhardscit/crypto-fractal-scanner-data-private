# Block 3 — Shadow Exit Engine

Generato: 2026-08-08T10:39:54+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **8**
- Scenari virtuali ancora attivi: **0**
- Gruppi in attesa dell'uscita originale: **8**
- Gruppi con originale chiuso ma Shadow ancora attive: **0**
- Confronti completati: **123297**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3277 | 3343 | +€9,06 | 51,5% | 923 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3277 | 3343 | +€7,42 | 50,6% | 923 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3277 | 3343 | +€6,64 | 43,1% | 711 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3277 | 3343 | +€6,19 | 49,0% | 923 | 80 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3277 | 3343 | +€5,07 | 33,1% | 412 | 383 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3277 | 3343 | +€4,83 | 48,5% | 1026 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3277 | 3343 | +€4,80 | 42,7% | 687 | 128 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3277 | 3343 | +€4,58 | 49,0% | 865 | 140 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3277 | 3343 | +€4,48 | 41,1% | 779 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3277 | 3343 | +€4,14 | 41,7% | 602 | 217 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3277 | 3343 | +€3,78 | 35,7% | 199 | 624 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3277 | 3343 | +€2,27 | 39,9% | 520 | 377 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3277 | 3343 | €-0,32 | 31,5% | 369 | 696 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3277 | 3343 | €-1,01 | 28,7% | 312 | 835 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3277 | 3343 | €-1,05 | 39,6% | 401 | 737 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3277 | 3343 | €-1,43 | 45,5% | 671 | 498 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3277 | 3343 | €-3,73 | 32,9% | 554 | 715 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3277 | 3343 | €-4,49 | 31,8% | 188 | 1003 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3277 | 3343 | €-5,32 | 27,3% | 261 | 912 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3277 | 3343 | €-8,62 | 22,6% | 261 | 1045 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
