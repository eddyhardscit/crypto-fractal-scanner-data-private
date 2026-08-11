# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T15:11:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **331**
- Scenari virtuali ancora attivi: **10356**
- Gruppi in attesa dell'uscita originale: **246**
- Gruppi con originale chiuso ma Shadow ancora attive: **85**
- Confronti completati: **136166**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3563 | 3629 | +€7,82 | 50,5% | 1000 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3563 | 3629 | +€6,71 | 49,4% | 985 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3563 | 3629 | +€3,70 | 47,5% | 1112 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3562 | 3628 | +€5,42 | 47,9% | 984 | 108 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3561 | 3627 | +€5,20 | 33,4% | 457 | 386 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3561 | 3627 | +€4,04 | 40,9% | 853 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3558 | 3624 | +€6,12 | 42,7% | 785 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3557 | 3623 | +€4,43 | 42,0% | 746 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3557 | 3623 | +€3,93 | 36,1% | 219 | 636 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3553 | 3619 | +€3,67 | 41,1% | 656 | 245 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3544 | 3610 | +€4,01 | 48,1% | 923 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3544 | 3610 | €-0,57 | 46,8% | 715 | 524 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3535 | 3601 | +€1,97 | 39,7% | 571 | 390 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3531 | 3597 | +€0,19 | 32,4% | 378 | 729 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3528 | 3594 | €-0,79 | 29,6% | 322 | 872 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3526 | 3592 | +€0,05 | 41,3% | 421 | 752 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3500 | 3566 | €-4,86 | 28,1% | 271 | 934 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3492 | 3558 | €-3,71 | 33,1% | 572 | 734 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3485 | 3551 | €-8,23 | 23,4% | 271 | 1067 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3478 | 3544 | €-4,16 | 32,2% | 199 | 1018 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
