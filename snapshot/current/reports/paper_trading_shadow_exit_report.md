# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T09:08:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **250**
- Scenari virtuali ancora attivi: **2783**
- Gruppi in attesa dell'uscita originale: **152**
- Gruppi con originale chiuso ma Shadow ancora attive: **98**
- Confronti completati: **8307**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 386 | 441 | +€7,87 | 47,2% | 102 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 386 | 441 | +€5,99 | 45,8% | 101 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 386 | 441 | +€4,11 | 45,1% | 102 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 386 | 441 | +€3,70 | 45,1% | 111 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 386 | 441 | +€2,14 | 44,2% | 97 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 377 | 432 | +€2,18 | 36,6% | 85 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 377 | 432 | +€1,16 | 35,6% | 78 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 377 | 432 | +€0,19 | 35,0% | 92 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 377 | 432 | €-0,61 | 50,9% | 88 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 362 | 417 | +€7,05 | 49,6% | 35 | 63 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 361 | 416 | €-0,86 | 27,6% | 42 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 358 | 413 | €-0,91 | 34,9% | 58 | 36 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 354 | 409 | €-1,53 | 31,8% | 34 | 71 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 348 | 403 | €-5,09 | 25,6% | 28 | 89 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 348 | 402 | €-7,12 | 28,9% | 67 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 344 | 399 | +€3,72 | 34,6% | 18 | 49 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 342 | 397 | €-7,65 | 22,9% | 23 | 99 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 331 | 386 | €-5,33 | 29,8% | 17 | 95 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 315 | 370 | €-12,34 | 21,1% | 20 | 87 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 309 | 362 | €-14,06 | 19,9% | 19 | 85 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
