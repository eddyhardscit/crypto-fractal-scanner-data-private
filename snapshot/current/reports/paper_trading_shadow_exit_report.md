# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T23:38:44+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **326**
- Scenari virtuali ancora attivi: **2930**
- Gruppi in attesa dell'uscita originale: **189**
- Gruppi con originale chiuso ma Shadow ancora attive: **137**
- Confronti completati: **13222**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 622 | 685 | +€6,04 | 46,4% | 172 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 622 | 685 | +€3,98 | 45,4% | 174 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 622 | 685 | +€1,79 | 44,2% | 177 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 622 | 685 | +€0,45 | 43,5% | 195 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 619 | 682 | +€0,61 | 42,7% | 169 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 618 | 681 | +€1,20 | 51,1% | 127 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 614 | 677 | +€3,76 | 38,1% | 148 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 614 | 677 | +€2,10 | 38,0% | 137 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 614 | 677 | +€1,20 | 37,5% | 114 | 55 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 614 | 677 | +€1,12 | 35,6% | 165 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 610 | 673 | +€1,16 | 34,5% | 81 | 103 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 605 | 668 | +€0,94 | 27,4% | 73 | 74 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 605 | 668 | €-0,55 | 31,9% | 36 | 149 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 595 | 658 | €-3,06 | 28,6% | 42 | 157 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 589 | 652 | +€0,33 | 33,1% | 34 | 112 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 588 | 651 | +€4,19 | 45,5% | 56 | 126 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 571 | 634 | €-8,24 | 24,1% | 38 | 158 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 568 | 631 | €-2,80 | 31,5% | 33 | 168 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 540 | 603 | €-7,30 | 28,2% | 95 | 88 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 510 | 573 | €-14,64 | 18,3% | 37 | 142 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
