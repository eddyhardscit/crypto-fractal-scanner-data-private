# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T22:38:42+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **326**
- Scenari virtuali ancora attivi: **2984**
- Gruppi in attesa dell'uscita originale: **189**
- Gruppi con originale chiuso ma Shadow ancora attive: **137**
- Confronti completati: **13203**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 622 | 685 | +€6,04 | 46,4% | 172 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 622 | 685 | +€3,98 | 45,4% | 174 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 622 | 685 | +€1,79 | 44,2% | 177 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 622 | 685 | +€0,45 | 43,5% | 195 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 618 | 681 | +€1,20 | 51,1% | 127 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 615 | 678 | +€0,78 | 42,9% | 169 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 614 | 677 | +€3,76 | 38,1% | 148 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 614 | 677 | +€2,10 | 38,0% | 137 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 614 | 677 | +€1,20 | 37,5% | 114 | 55 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 614 | 677 | +€1,12 | 35,6% | 165 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 606 | 669 | +€1,33 | 34,7% | 81 | 99 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 605 | 668 | +€0,94 | 27,4% | 73 | 74 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 600 | 663 | €-0,21 | 32,1% | 36 | 144 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 594 | 657 | €-3,01 | 28,6% | 42 | 156 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 589 | 652 | +€0,33 | 33,1% | 34 | 112 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 586 | 649 | +€3,99 | 45,3% | 56 | 126 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 570 | 633 | €-8,20 | 24,2% | 38 | 157 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 568 | 631 | €-2,80 | 31,5% | 33 | 168 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 539 | 602 | €-7,25 | 28,2% | 95 | 87 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 509 | 572 | €-14,60 | 18,4% | 37 | 141 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
