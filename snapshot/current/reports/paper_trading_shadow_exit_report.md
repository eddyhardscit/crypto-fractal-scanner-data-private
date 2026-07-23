# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T16:38:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **306**
- Scenari virtuali ancora attivi: **2995**
- Gruppi in attesa dell'uscita originale: **172**
- Gruppi con originale chiuso ma Shadow ancora attive: **134**
- Confronti completati: **12177**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R050 | 577 | 639 | +€0,70 | 42,3% | 180 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 574 | 636 | +€5,84 | 44,8% | 159 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 574 | 636 | +€3,86 | 43,7% | 161 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 574 | 636 | +€1,76 | 42,9% | 163 | 11 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 569 | 631 | +€0,54 | 33,6% | 152 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 568 | 630 | +€0,12 | 41,1% | 160 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 566 | 628 | +€2,98 | 35,7% | 137 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 566 | 628 | +€1,24 | 35,0% | 129 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 558 | 620 | €-0,45 | 34,5% | 106 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 556 | 618 | +€0,59 | 25,7% | 68 | 65 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 552 | 614 | €-0,29 | 50,0% | 125 | 71 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 544 | 606 | €-0,42 | 31,5% | 75 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 537 | 599 | +€1,13 | 42,9% | 54 | 119 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 537 | 599 | +€0,23 | 30,9% | 29 | 99 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 534 | 596 | €-2,98 | 27,9% | 35 | 129 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 531 | 593 | €-3,30 | 29,8% | 31 | 159 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 528 | 590 | €-4,77 | 24,4% | 41 | 138 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 514 | 576 | €-8,85 | 20,5% | 37 | 140 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 502 | 564 | €-7,71 | 26,1% | 90 | 80 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 477 | 538 | €-15,47 | 15,4% | 36 | 134 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
