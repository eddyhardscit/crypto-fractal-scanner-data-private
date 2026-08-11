# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T17:26:16+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **401**
- Scenari virtuali ancora attivi: **11161**
- Gruppi in attesa dell'uscita originale: **264**
- Gruppi con originale chiuso ma Shadow ancora attive: **137**
- Confronti completati: **138589**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3626 | 3692 | +€7,49 | 50,2% | 1029 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3626 | 3692 | +€6,35 | 49,2% | 1014 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3626 | 3692 | +€3,36 | 47,2% | 1144 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3624 | 3690 | +€3,94 | 40,8% | 881 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3620 | 3686 | +€6,07 | 42,7% | 809 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3620 | 3686 | +€5,05 | 47,7% | 1009 | 108 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3614 | 3680 | +€4,40 | 42,1% | 766 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3610 | 3676 | +€3,60 | 41,2% | 675 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3608 | 3674 | €-1,19 | 46,0% | 749 | 540 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3602 | 3668 | +€5,12 | 33,1% | 469 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3602 | 3668 | +€3,62 | 47,9% | 949 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3597 | 3663 | +€3,98 | 36,1% | 226 | 636 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3592 | 3658 | +€1,86 | 39,8% | 589 | 390 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3591 | 3657 | +€0,27 | 32,7% | 393 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3574 | 3640 | €-0,17 | 41,1% | 443 | 754 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3573 | 3639 | €-0,70 | 30,1% | 323 | 874 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3534 | 3600 | €-4,84 | 27,8% | 272 | 952 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3519 | 3585 | €-3,75 | 32,8% | 575 | 743 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3510 | 3576 | €-8,19 | 23,3% | 272 | 1076 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3489 | 3555 | €-4,15 | 32,1% | 199 | 1018 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
