# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T15:39:13+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **685**
- Scenari virtuali ancora attivi: **10043**
- Gruppi in attesa dell'uscita originale: **208**
- Gruppi con originale chiuso ma Shadow ancora attive: **477**
- Confronti completati: **96534**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2803 | 2868 | €-2,65 | 45,1% | 621 | 445 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2787 | 2852 | +€7,81 | 50,3% | 838 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2787 | 2852 | +€6,16 | 49,3% | 840 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2787 | 2852 | +€3,49 | 47,0% | 936 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2780 | 2845 | +€4,07 | 47,7% | 847 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2764 | 2829 | +€2,64 | 47,6% | 795 | 107 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2762 | 2827 | €-2,29 | 38,9% | 362 | 676 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2741 | 2806 | +€4,28 | 41,6% | 741 | 74 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2740 | 2805 | +€6,58 | 44,0% | 671 | 76 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2740 | 2805 | +€4,67 | 43,9% | 642 | 110 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2740 | 2805 | +€3,09 | 43,2% | 556 | 185 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2731 | 2796 | €-2,18 | 32,3% | 355 | 606 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2723 | 2788 | +€1,31 | 41,2% | 478 | 330 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2717 | 2782 | €-2,35 | 29,7% | 301 | 712 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2645 | 2710 | +€5,34 | 32,9% | 403 | 284 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2601 | 2666 | €-4,56 | 33,0% | 169 | 775 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2593 | 2658 | €-7,92 | 31,6% | 502 | 530 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2583 | 2648 | +€4,96 | 37,0% | 196 | 443 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2581 | 2646 | €-7,37 | 27,1% | 250 | 713 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2507 | 2572 | €-13,81 | 21,7% | 249 | 795 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
