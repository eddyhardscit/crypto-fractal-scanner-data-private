# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T07:08:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **236**
- Scenari virtuali ancora attivi: **2613**
- Gruppi in attesa dell'uscita originale: **137**
- Gruppi con originale chiuso ma Shadow ancora attive: **99**
- Confronti completati: **7741**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 357 | 407 | +€6,87 | 46,4% | 97 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 357 | 407 | +€4,93 | 45,0% | 96 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 357 | 407 | +€3,23 | 44,2% | 106 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 357 | 407 | +€3,08 | 44,2% | 97 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 357 | 407 | +€1,06 | 43,2% | 92 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 357 | 412 | €-1,91 | 49,0% | 87 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 355 | 405 | €-0,24 | 34,3% | 88 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 354 | 404 | +€1,32 | 35,9% | 81 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 347 | 397 | €-0,03 | 34,3% | 74 | 25 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 339 | 394 | +€6,04 | 47,2% | 34 | 63 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 339 | 389 | €-1,52 | 26,7% | 40 | 45 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 335 | 385 | €-1,87 | 34,0% | 54 | 36 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 333 | 383 | €-2,42 | 31,1% | 30 | 71 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 329 | 379 | €-6,29 | 24,3% | 26 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 322 | 372 | +€3,03 | 33,6% | 16 | 48 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 322 | 372 | €-8,88 | 21,5% | 21 | 98 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 321 | 371 | €-7,70 | 28,8% | 65 | 46 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 305 | 360 | €-5,52 | 28,9% | 17 | 91 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 295 | 345 | €-13,71 | 19,7% | 18 | 85 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 289 | 338 | €-14,90 | 18,9% | 17 | 83 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
