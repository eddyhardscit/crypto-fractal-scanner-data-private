# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T21:23:39+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **266**
- Scenari virtuali ancora attivi: **2521**
- Gruppi in attesa dell'uscita originale: **153**
- Gruppi con originale chiuso ma Shadow ancora attive: **113**
- Confronti completati: **10260**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 471 | 532 | +€8,34 | 47,4% | 123 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 471 | 532 | +€6,55 | 46,2% | 123 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 471 | 532 | +€4,53 | 45,5% | 124 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 471 | 532 | +€3,68 | 45,9% | 132 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 471 | 532 | +€2,57 | 44,7% | 119 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 470 | 531 | €-0,89 | 49,9% | 109 | 60 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 464 | 525 | +€4,67 | 37,7% | 105 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 464 | 525 | +€2,34 | 36,4% | 112 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 463 | 524 | +€3,21 | 37,2% | 96 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 463 | 524 | +€1,87 | 37,2% | 76 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 461 | 522 | +€1,04 | 34,9% | 51 | 83 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 459 | 520 | +€1,90 | 43,7% | 41 | 110 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 455 | 516 | €-2,95 | 29,1% | 33 | 111 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 449 | 510 | €-4,95 | 24,9% | 39 | 121 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 440 | 501 | +€1,34 | 27,9% | 48 | 53 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 435 | 496 | €-7,93 | 22,2% | 35 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 431 | 492 | €-3,72 | 29,7% | 22 | 133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 427 | 488 | €-7,11 | 26,8% | 85 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 415 | 476 | €-0,69 | 30,5% | 20 | 81 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 390 | 450 | €-13,55 | 17,1% | 34 | 100 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
