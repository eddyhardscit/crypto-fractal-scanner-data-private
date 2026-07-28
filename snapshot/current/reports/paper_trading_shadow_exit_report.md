# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T20:53:59+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **660**
- Scenari virtuali ancora attivi: **10625**
- Gruppi in attesa dell'uscita originale: **223**
- Gruppi con originale chiuso ma Shadow ancora attive: **437**
- Confronti completati: **101807**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 2894 | 2959 | €-2,31 | 39,1% | 371 | 717 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2894 | 2959 | €-2,40 | 46,0% | 630 | 446 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2889 | 2954 | +€8,14 | 51,2% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2889 | 2954 | +€6,50 | 50,2% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2889 | 2954 | +€3,89 | 48,0% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2882 | 2947 | +€4,42 | 48,7% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2866 | 2931 | +€3,04 | 48,6% | 805 | 109 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2847 | 2912 | +€6,34 | 44,1% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2847 | 2912 | +€4,47 | 44,0% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2847 | 2912 | +€4,14 | 41,8% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2847 | 2912 | +€2,93 | 43,4% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2831 | 2896 | +€1,20 | 41,4% | 486 | 340 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2829 | 2894 | €-2,15 | 32,9% | 355 | 614 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2812 | 2877 | €-2,30 | 30,3% | 301 | 719 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2803 | 2868 | €-4,88 | 33,3% | 169 | 863 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2782 | 2847 | +€4,74 | 33,1% | 403 | 320 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2750 | 2815 | €-6,52 | 28,3% | 250 | 762 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2712 | 2777 | +€4,28 | 37,0% | 196 | 484 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2692 | 2757 | €-6,92 | 33,3% | 504 | 534 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2615 | 2680 | €-12,70 | 22,9% | 249 | 806 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
