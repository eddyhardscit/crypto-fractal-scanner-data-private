# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T04:54:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **454**
- Scenari virtuali ancora attivi: **10541**
- Gruppi in attesa dell'uscita originale: **275**
- Gruppi con originale chiuso ma Shadow ancora attive: **179**
- Confronti completati: **179729**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4433 | 4499 | +€8,08 | 50,3% | 1162 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4433 | 4499 | +€7,13 | 49,3% | 1154 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4433 | 4499 | +€6,59 | 42,7% | 905 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4433 | 4499 | +€5,05 | 41,9% | 873 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4433 | 4499 | +€4,55 | 47,6% | 1290 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4433 | 4499 | +€4,53 | 40,7% | 1003 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4430 | 4496 | +€5,85 | 47,7% | 1165 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4430 | 4496 | +€4,53 | 48,0% | 1093 | 171 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4430 | 4496 | +€4,29 | 41,3% | 763 | 279 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4429 | 4495 | €-0,31 | 46,0% | 827 | 645 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4427 | 4493 | +€2,56 | 40,2% | 640 | 470 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4419 | 4485 | €-0,66 | 40,1% | 471 | 924 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4415 | 4481 | +€0,89 | 33,6% | 454 | 827 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4415 | 4481 | €-0,02 | 31,4% | 327 | 1042 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4413 | 4479 | +€5,20 | 32,9% | 541 | 446 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4388 | 4454 | €-4,74 | 28,1% | 276 | 1189 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4385 | 4451 | +€4,78 | 36,1% | 254 | 705 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4362 | 4428 | €-3,82 | 33,6% | 640 | 930 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4353 | 4419 | €-8,72 | 23,8% | 276 | 1332 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4310 | 4376 | €-5,71 | 31,1% | 209 | 1245 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
