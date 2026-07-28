# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T19:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **692**
- Scenari virtuali ancora attivi: **12582**
- Gruppi in attesa dell'uscita originale: **254**
- Gruppi con originale chiuso ma Shadow ancora attive: **438**
- Confronti completati: **99396**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2847 | 2912 | €-2,55 | 45,2% | 630 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2845 | 2910 | €-2,44 | 38,1% | 371 | 715 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2841 | 2906 | +€8,16 | 50,4% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2841 | 2906 | +€6,49 | 49,4% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2841 | 2906 | +€3,84 | 47,2% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2834 | 2899 | +€4,38 | 47,9% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2818 | 2883 | +€2,98 | 47,8% | 805 | 109 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2799 | 2864 | +€6,34 | 43,3% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2799 | 2864 | +€4,43 | 43,1% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2799 | 2864 | +€4,10 | 40,9% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2799 | 2864 | +€2,86 | 42,5% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2783 | 2848 | +€1,11 | 40,4% | 486 | 340 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2781 | 2846 | €-2,30 | 31,8% | 355 | 614 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2764 | 2829 | €-2,46 | 29,2% | 301 | 719 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2739 | 2804 | €-5,03 | 32,2% | 169 | 850 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2734 | 2799 | +€4,71 | 32,0% | 403 | 320 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2702 | 2767 | €-6,75 | 27,1% | 250 | 762 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2664 | 2729 | +€4,23 | 36,0% | 196 | 484 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2644 | 2709 | €-7,16 | 32,2% | 504 | 534 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2567 | 2632 | €-13,06 | 21,6% | 249 | 806 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
