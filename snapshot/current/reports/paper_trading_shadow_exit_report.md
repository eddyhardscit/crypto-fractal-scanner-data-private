# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T12:08:24+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **536**
- Scenari virtuali ancora attivi: **12273**
- Gruppi in attesa dell'uscita originale: **336**
- Gruppi con originale chiuso ma Shadow ancora attive: **200**
- Confronti completati: **180778**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4457 | 4523 | +€8,02 | 50,2% | 1178 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4457 | 4523 | +€7,07 | 49,2% | 1170 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4457 | 4523 | +€6,57 | 42,7% | 917 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4457 | 4523 | +€5,02 | 41,9% | 883 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4457 | 4523 | +€4,52 | 40,7% | 1015 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4457 | 4523 | +€4,47 | 47,5% | 1306 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4457 | 4523 | €-0,31 | 46,0% | 839 | 649 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4456 | 4522 | +€5,80 | 47,5% | 1179 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4456 | 4522 | +€4,47 | 47,9% | 1107 | 176 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4456 | 4522 | +€4,25 | 41,2% | 776 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4456 | 4522 | +€2,52 | 40,1% | 652 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4447 | 4513 | €-0,81 | 39,9% | 481 | 940 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4445 | 4511 | +€5,30 | 33,1% | 549 | 446 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4437 | 4503 | +€0,84 | 33,5% | 463 | 833 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4434 | 4500 | +€5,19 | 36,6% | 255 | 705 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4428 | 4494 | €-0,07 | 31,3% | 335 | 1045 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4392 | 4458 | €-4,74 | 28,1% | 278 | 1189 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4371 | 4437 | €-3,81 | 33,6% | 647 | 930 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4359 | 4425 | €-5,66 | 31,4% | 209 | 1260 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4357 | 4423 | €-8,72 | 23,8% | 278 | 1332 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
