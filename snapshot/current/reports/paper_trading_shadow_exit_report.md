# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T18:38:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **320**
- Scenari virtuali ancora attivi: **3033**
- Gruppi in attesa dell'uscita originale: **172**
- Gruppi con originale chiuso ma Shadow ancora attive: **148**
- Confronti completati: **12856**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 609 | 671 | +€6,42 | 46,5% | 166 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 609 | 671 | +€4,36 | 45,5% | 168 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 609 | 671 | +€2,19 | 44,6% | 170 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 609 | 671 | +€0,90 | 43,8% | 187 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 606 | 668 | +€0,84 | 43,1% | 166 | 21 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 601 | 663 | +€3,97 | 37,9% | 143 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 601 | 663 | +€1,30 | 35,4% | 159 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 600 | 662 | +€2,10 | 37,2% | 135 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 600 | 662 | +€1,30 | 37,5% | 111 | 51 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 597 | 659 | +€1,39 | 34,7% | 78 | 97 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 593 | 655 | €-0,19 | 32,1% | 35 | 142 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 586 | 648 | +€0,46 | 26,7% | 71 | 72 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 580 | 642 | +€0,03 | 50,9% | 126 | 78 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 577 | 639 | €-2,60 | 28,8% | 41 | 145 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 563 | 625 | +€0,17 | 31,8% | 32 | 106 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 562 | 624 | +€1,14 | 44,1% | 55 | 125 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 555 | 617 | €-2,95 | 31,3% | 32 | 165 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 535 | 597 | €-7,92 | 22,9% | 37 | 140 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 527 | 589 | €-6,76 | 28,4% | 93 | 81 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 498 | 559 | €-14,23 | 18,2% | 36 | 134 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
