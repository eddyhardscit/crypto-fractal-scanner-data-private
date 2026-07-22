# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T06:08:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **237**
- Scenari virtuali ancora attivi: **2637**
- Gruppi in attesa dell'uscita originale: **141**
- Gruppi con originale chiuso ma Shadow ancora attive: **96**
- Confronti completati: **7404**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 339 | 389 | +€7,81 | 47,6% | 90 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 339 | 389 | +€5,86 | 46,0% | 89 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 339 | 389 | +€3,99 | 45,2% | 90 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 339 | 389 | +€3,91 | 45,2% | 99 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 339 | 389 | +€1,92 | 44,2% | 85 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 339 | 394 | €-1,46 | 48,5% | 80 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 335 | 385 | +€0,89 | 36,1% | 81 | 14 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 334 | 384 | +€2,59 | 37,8% | 74 | 14 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 330 | 380 | +€0,87 | 35,8% | 70 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 322 | 372 | €-1,67 | 35,2% | 54 | 34 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 319 | 369 | €-0,90 | 28,2% | 33 | 43 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 319 | 369 | €-2,12 | 32,2% | 30 | 68 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 318 | 373 | +€2,89 | 44,2% | 34 | 63 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 316 | 366 | €-6,24 | 25,1% | 26 | 87 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 309 | 359 | €-8,93 | 22,3% | 21 | 96 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 307 | 357 | €-7,71 | 28,9% | 62 | 46 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 302 | 352 | +€3,45 | 34,9% | 15 | 46 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 290 | 345 | €-5,52 | 29,6% | 17 | 88 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 281 | 331 | €-13,85 | 20,5% | 18 | 82 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 274 | 323 | €-14,82 | 19,8% | 17 | 79 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
