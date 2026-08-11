# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T20:25:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **403**
- Scenari virtuali ancora attivi: **10379**
- Gruppi in attesa dell'uscita originale: **246**
- Gruppi con originale chiuso ma Shadow ancora attive: **157**
- Confronti completati: **143986**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3725 | 3791 | +€7,51 | 50,2% | 1039 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3725 | 3791 | +€6,37 | 49,1% | 1028 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3725 | 3791 | +€5,05 | 47,2% | 1038 | 113 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3725 | 3791 | +€4,27 | 41,1% | 886 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3725 | 3791 | +€3,49 | 47,3% | 1154 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3717 | 3783 | +€6,29 | 42,9% | 811 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3717 | 3783 | +€4,65 | 42,3% | 768 | 161 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3717 | 3783 | +€3,84 | 41,5% | 676 | 254 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3715 | 3781 | +€0,73 | 33,0% | 396 | 755 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3712 | 3778 | €-0,63 | 30,1% | 325 | 927 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3706 | 3772 | +€3,68 | 47,4% | 977 | 159 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3703 | 3769 | +€5,45 | 33,3% | 472 | 400 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3699 | 3765 | €-1,23 | 45,2% | 772 | 553 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3697 | 3763 | +€4,50 | 36,2% | 227 | 653 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3694 | 3760 | +€2,09 | 40,0% | 592 | 397 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3667 | 3733 | €-0,36 | 40,7% | 450 | 773 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3652 | 3718 | €-5,20 | 27,1% | 274 | 1020 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3644 | 3710 | €-4,13 | 32,0% | 597 | 797 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3637 | 3703 | €-8,53 | 22,6% | 274 | 1153 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3568 | 3634 | €-4,74 | 31,5% | 200 | 1050 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
