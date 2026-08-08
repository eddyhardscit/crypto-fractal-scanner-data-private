# Block 3 — Shadow Exit Engine

Generato: 2026-08-08T20:39:00+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **13**
- Scenari virtuali ancora attivi: **195**
- Gruppi in attesa dell'uscita originale: **8**
- Gruppi con originale chiuso ma Shadow ancora attive: **5**
- Confronti completati: **123600**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3284 | 3350 | +€9,07 | 51,5% | 925 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3284 | 3350 | +€7,43 | 50,6% | 925 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3284 | 3350 | +€6,65 | 43,1% | 711 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3284 | 3350 | +€6,20 | 49,0% | 926 | 80 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3284 | 3350 | +€4,84 | 48,5% | 1028 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3284 | 3350 | +€4,82 | 42,7% | 687 | 128 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3284 | 3350 | +€4,59 | 48,9% | 868 | 140 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3284 | 3350 | +€4,50 | 41,1% | 779 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3284 | 3350 | +€4,16 | 41,7% | 604 | 217 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3284 | 3350 | +€2,29 | 39,9% | 520 | 377 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3284 | 3350 | €-3,71 | 32,8% | 557 | 715 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3281 | 3347 | +€5,08 | 33,1% | 412 | 383 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3281 | 3347 | +€3,79 | 35,6% | 199 | 624 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3281 | 3347 | €-0,31 | 31,5% | 369 | 696 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3281 | 3347 | €-0,99 | 28,7% | 312 | 835 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3281 | 3347 | €-1,04 | 39,6% | 401 | 737 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3281 | 3347 | €-1,42 | 45,5% | 671 | 498 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3281 | 3347 | €-4,47 | 31,8% | 188 | 1003 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3281 | 3347 | €-5,30 | 27,2% | 261 | 912 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3281 | 3347 | €-8,59 | 22,6% | 261 | 1045 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
