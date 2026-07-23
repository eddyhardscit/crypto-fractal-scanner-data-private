# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T19:38:42+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **331**
- Scenari virtuali ancora attivi: **3181**
- Gruppi in attesa dell'uscita originale: **184**
- Gruppi con originale chiuso ma Shadow ancora attive: **147**
- Confronti completati: **13021**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 613 | 676 | +€6,42 | 46,7% | 167 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 613 | 676 | +€4,36 | 45,7% | 169 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 613 | 676 | +€2,19 | 44,7% | 171 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 613 | 676 | +€0,83 | 43,9% | 189 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 610 | 673 | +€0,83 | 43,2% | 167 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 605 | 668 | +€3,99 | 38,2% | 144 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 605 | 668 | +€2,14 | 37,6% | 136 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 605 | 668 | +€1,30 | 37,7% | 112 | 52 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 605 | 668 | +€1,26 | 35,6% | 161 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 602 | 665 | +€1,35 | 34,9% | 79 | 99 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 597 | 660 | €-0,19 | 32,3% | 36 | 143 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 596 | 659 | +€0,63 | 51,0% | 126 | 83 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 591 | 654 | €-2,98 | 28,7% | 42 | 155 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 590 | 653 | +€0,46 | 27,0% | 72 | 72 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 567 | 630 | +€1,22 | 44,1% | 55 | 125 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 567 | 630 | +€0,22 | 32,2% | 33 | 106 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 566 | 629 | €-8,08 | 24,3% | 38 | 155 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 563 | 626 | €-2,77 | 31,5% | 32 | 167 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 535 | 598 | €-7,11 | 28,4% | 94 | 86 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 506 | 568 | €-14,48 | 18,5% | 37 | 139 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
