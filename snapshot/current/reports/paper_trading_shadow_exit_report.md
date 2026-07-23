# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T15:38:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **292**
- Scenari virtuali ancora attivi: **2889**
- Gruppi in attesa dell'uscita originale: **179**
- Gruppi con originale chiuso ma Shadow ancora attive: **113**
- Confronti completati: **11835**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R050 | 553 | 615 | +€2,74 | 43,6% | 161 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 552 | 614 | +€7,98 | 46,1% | 143 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 552 | 614 | +€6,05 | 45,1% | 144 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 552 | 614 | +€3,99 | 44,3% | 146 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 549 | 611 | +€2,16 | 42,4% | 145 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 543 | 605 | +€3,83 | 35,7% | 125 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 543 | 605 | +€2,21 | 35,2% | 116 | 31 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 543 | 605 | +€1,63 | 34,2% | 134 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 543 | 605 | +€0,72 | 35,2% | 95 | 50 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 539 | 601 | €-0,18 | 31,8% | 73 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 538 | 600 | +€1,33 | 50,8% | 116 | 71 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 529 | 591 | +€0,67 | 25,9% | 56 | 65 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 526 | 588 | +€2,80 | 43,7% | 46 | 119 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 520 | 582 | €-2,45 | 30,4% | 23 | 159 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 519 | 581 | €-3,17 | 27,5% | 35 | 123 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 515 | 577 | €-5,40 | 23,4% | 41 | 137 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 511 | 573 | €-8,90 | 20,6% | 37 | 140 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 499 | 561 | €-1,24 | 28,9% | 23 | 99 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 496 | 558 | €-7,30 | 26,3% | 88 | 79 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 474 | 535 | €-15,56 | 15,5% | 36 | 134 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
