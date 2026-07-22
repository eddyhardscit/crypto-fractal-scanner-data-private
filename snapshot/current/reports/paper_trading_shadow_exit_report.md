# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T15:23:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **278**
- Scenari virtuali ancora attivi: **3161**
- Gruppi in attesa dell'uscita originale: **176**
- Gruppi con originale chiuso ma Shadow ancora attive: **102**
- Confronti completati: **8730**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 400 | 461 | +€8,40 | 47,9% | 106 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 400 | 461 | +€6,44 | 46,6% | 105 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 400 | 461 | +€4,51 | 46,0% | 106 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 400 | 461 | +€3,76 | 46,0% | 115 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 400 | 461 | +€2,70 | 45,1% | 101 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 395 | 456 | €-0,24 | 52,2% | 92 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 388 | 449 | +€6,55 | 49,7% | 39 | 74 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 386 | 447 | +€2,82 | 37,1% | 89 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 386 | 447 | +€1,79 | 36,5% | 81 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 386 | 447 | +€0,89 | 36,5% | 62 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 386 | 447 | +€0,54 | 35,6% | 96 | 16 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 384 | 445 | €-2,88 | 28,5% | 32 | 100 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 372 | 433 | +€0,19 | 28,9% | 46 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 364 | 425 | €-0,71 | 32,7% | 37 | 72 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 364 | 424 | €-7,45 | 28,3% | 72 | 51 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 355 | 416 | +€4,34 | 34,9% | 19 | 52 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 353 | 414 | €-6,94 | 23,7% | 27 | 102 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 346 | 407 | €-5,55 | 30,5% | 20 | 101 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 328 | 389 | €-11,85 | 21,3% | 24 | 92 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 320 | 379 | €-14,21 | 20,1% | 23 | 88 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
