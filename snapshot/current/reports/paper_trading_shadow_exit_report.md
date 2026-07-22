# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T17:23:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **295**
- Scenari virtuali ancora attivi: **2960**
- Gruppi in attesa dell'uscita originale: **171**
- Gruppi con originale chiuso ma Shadow ancora attive: **124**
- Confronti completati: **9158**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 427 | 488 | +€7,09 | 46,7% | 121 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 427 | 488 | +€5,32 | 45,5% | 121 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 427 | 488 | +€3,33 | 44,9% | 121 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 427 | 488 | +€2,37 | 45,1% | 130 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 427 | 488 | +€1,39 | 44,1% | 116 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 420 | 481 | +€3,65 | 37,6% | 104 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 420 | 481 | +€2,27 | 37,0% | 96 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 420 | 481 | +€1,19 | 36,2% | 111 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 420 | 481 | +€1,03 | 37,0% | 76 | 45 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 418 | 479 | €-0,13 | 51,8% | 103 | 51 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 403 | 464 | +€2,01 | 29,5% | 47 | 46 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 397 | 458 | +€6,15 | 48,7% | 39 | 79 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 397 | 458 | €-0,96 | 33,4% | 51 | 73 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 390 | 451 | €-2,84 | 28,2% | 32 | 100 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 376 | 436 | €-7,41 | 28,2% | 73 | 52 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 363 | 424 | €-0,53 | 32,3% | 20 | 101 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 361 | 422 | +€4,13 | 34,4% | 19 | 53 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 361 | 422 | €-6,78 | 23,5% | 27 | 103 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 334 | 395 | €-11,67 | 21,0% | 24 | 92 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 326 | 385 | €-13,99 | 19,7% | 23 | 88 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
