# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T10:08:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **255**
- Scenari virtuali ancora attivi: **2942**
- Gruppi in attesa dell'uscita originale: **156**
- Gruppi con originale chiuso ma Shadow ancora attive: **99**
- Confronti completati: **8415**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 387 | 446 | +€7,98 | 47,1% | 105 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 387 | 446 | +€6,02 | 45,7% | 104 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 387 | 446 | +€4,07 | 45,1% | 105 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 387 | 446 | +€3,32 | 45,1% | 114 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 387 | 446 | +€2,26 | 44,2% | 100 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 378 | 437 | +€2,36 | 36,6% | 88 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 378 | 437 | +€1,26 | 35,7% | 81 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 378 | 437 | +€0,08 | 35,0% | 95 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 377 | 436 | €-1,19 | 50,7% | 91 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 364 | 423 | +€6,51 | 49,6% | 38 | 63 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 362 | 421 | €-0,72 | 27,8% | 45 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 359 | 418 | €-0,89 | 34,9% | 61 | 36 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 355 | 414 | €-1,36 | 31,9% | 37 | 71 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 351 | 410 | €-4,99 | 25,4% | 32 | 91 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 351 | 409 | €-7,78 | 28,4% | 71 | 50 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 345 | 404 | €-7,61 | 22,8% | 27 | 101 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 344 | 403 | +€4,05 | 34,5% | 19 | 49 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 331 | 390 | €-5,93 | 29,7% | 20 | 95 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 318 | 377 | €-12,08 | 21,0% | 24 | 89 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 312 | 369 | €-14,67 | 19,5% | 23 | 87 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
