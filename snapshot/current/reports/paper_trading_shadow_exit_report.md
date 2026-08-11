# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T16:25:29+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **387**
- Scenari virtuali ancora attivi: **11434**
- Gruppi in attesa dell'uscita originale: **275**
- Gruppi con originale chiuso ma Shadow ancora attive: **112**
- Confronti completati: **137040**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3590 | 3656 | +€7,84 | 50,6% | 1008 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3590 | 3656 | +€6,72 | 49,6% | 993 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3590 | 3656 | +€3,68 | 47,6% | 1123 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3588 | 3654 | +€4,11 | 41,1% | 860 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3586 | 3652 | +€6,25 | 43,0% | 790 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3584 | 3650 | +€5,43 | 48,1% | 988 | 108 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3580 | 3646 | +€4,55 | 42,4% | 747 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3576 | 3642 | +€3,77 | 41,5% | 657 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3570 | 3636 | +€5,20 | 33,4% | 464 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3566 | 3632 | +€4,00 | 48,2% | 928 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3565 | 3631 | +€3,92 | 36,0% | 222 | 636 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3563 | 3629 | €-0,68 | 46,5% | 724 | 533 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3561 | 3627 | +€0,32 | 32,9% | 378 | 729 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3558 | 3624 | +€2,06 | 40,0% | 571 | 390 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3558 | 3624 | €-0,71 | 30,1% | 323 | 874 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3540 | 3606 | +€0,10 | 41,4% | 425 | 752 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3505 | 3571 | €-4,85 | 28,1% | 272 | 934 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3497 | 3563 | €-3,71 | 33,0% | 573 | 734 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3490 | 3556 | €-8,22 | 23,4% | 272 | 1067 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3478 | 3544 | €-4,16 | 32,2% | 199 | 1018 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
