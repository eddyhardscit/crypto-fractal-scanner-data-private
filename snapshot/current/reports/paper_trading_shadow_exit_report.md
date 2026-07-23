# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T17:38:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **318**
- Scenari virtuali ancora attivi: **3144**
- Gruppi in attesa dell'uscita originale: **180**
- Gruppi con originale chiuso ma Shadow ancora attive: **138**
- Confronti completati: **12238**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 581 | 643 | +€5,68 | 44,9% | 162 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 581 | 643 | +€3,65 | 43,9% | 164 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 581 | 643 | +€1,49 | 42,9% | 166 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 581 | 643 | +€0,27 | 42,1% | 183 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 572 | 634 | +€2,96 | 35,8% | 140 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 572 | 634 | +€1,15 | 35,2% | 132 | 31 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 572 | 634 | +€0,21 | 33,4% | 155 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 571 | 633 | €-0,22 | 41,1% | 162 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 563 | 625 | €-0,55 | 34,6% | 108 | 51 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 559 | 621 | +€0,37 | 25,6% | 71 | 65 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 555 | 617 | €-0,37 | 49,9% | 126 | 72 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 544 | 606 | €-0,42 | 31,5% | 75 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 540 | 602 | +€0,13 | 30,7% | 32 | 99 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 538 | 600 | +€0,85 | 42,8% | 55 | 119 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 534 | 596 | €-2,98 | 27,9% | 35 | 129 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 533 | 595 | €-3,34 | 29,9% | 32 | 159 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 528 | 590 | €-4,77 | 24,4% | 41 | 138 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 514 | 576 | €-8,85 | 20,5% | 37 | 140 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 503 | 565 | €-7,72 | 26,0% | 90 | 81 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 477 | 538 | €-15,47 | 15,4% | 36 | 134 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
