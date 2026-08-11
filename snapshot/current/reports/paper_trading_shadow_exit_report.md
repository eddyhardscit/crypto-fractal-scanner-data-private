# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T19:25:06+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **453**
- Scenari virtuali ancora attivi: **12694**
- Gruppi in attesa dell'uscita originale: **276**
- Gruppi con originale chiuso ma Shadow ancora attive: **177**
- Confronti completati: **141346**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3682 | 3748 | +€7,46 | 50,6% | 1032 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3682 | 3748 | +€6,31 | 49,5% | 1022 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3682 | 3748 | +€3,40 | 47,7% | 1147 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3680 | 3746 | +€6,26 | 43,2% | 811 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3680 | 3746 | +€4,23 | 41,4% | 884 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3676 | 3742 | +€4,99 | 47,6% | 1032 | 108 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3676 | 3742 | +€4,64 | 42,6% | 768 | 157 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3666 | 3732 | +€3,81 | 41,8% | 676 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3658 | 3724 | €-1,29 | 45,6% | 772 | 549 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3656 | 3722 | +€3,61 | 47,8% | 970 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3646 | 3712 | +€2,02 | 40,4% | 591 | 390 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3645 | 3711 | +€0,56 | 33,2% | 396 | 735 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3644 | 3710 | +€5,53 | 33,6% | 470 | 386 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3638 | 3704 | +€4,60 | 36,6% | 227 | 636 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3630 | 3696 | €-0,75 | 30,4% | 325 | 891 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3617 | 3683 | €-0,27 | 41,2% | 450 | 759 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3602 | 3668 | €-5,25 | 27,4% | 274 | 1006 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3586 | 3652 | €-4,15 | 32,3% | 597 | 775 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3579 | 3645 | €-8,56 | 22,9% | 274 | 1131 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3505 | 3571 | €-4,31 | 31,9% | 200 | 1023 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
