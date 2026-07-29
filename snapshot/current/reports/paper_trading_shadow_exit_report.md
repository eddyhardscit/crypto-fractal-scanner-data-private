# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T00:53:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **674**
- Scenari virtuali ancora attivi: **11831**
- Gruppi in attesa dell'uscita originale: **251**
- Gruppi con originale chiuso ma Shadow ancora attive: **423**
- Confronti completati: **104191**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2944 | 3009 | €-2,36 | 46,3% | 632 | 457 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2936 | 3001 | +€8,52 | 51,5% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2936 | 3001 | +€6,87 | 50,5% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2936 | 3001 | +€4,30 | 48,3% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2929 | 2994 | +€4,80 | 49,0% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2928 | 2993 | €-2,25 | 39,2% | 371 | 720 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2927 | 2992 | +€3,36 | 48,7% | 805 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2904 | 2969 | +€6,38 | 44,3% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2904 | 2969 | +€4,52 | 44,2% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2904 | 2969 | +€4,24 | 42,0% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2904 | 2969 | +€2,99 | 43,6% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2902 | 2967 | +€1,23 | 41,4% | 486 | 354 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2894 | 2959 | €-4,99 | 33,1% | 169 | 913 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2880 | 2945 | €-2,12 | 32,8% | 360 | 617 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2864 | 2929 | €-2,30 | 30,4% | 306 | 723 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2839 | 2904 | +€4,72 | 33,1% | 403 | 329 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2799 | 2864 | €-6,38 | 28,4% | 255 | 763 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2780 | 2845 | +€4,35 | 37,2% | 196 | 495 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2736 | 2801 | €-6,25 | 33,6% | 509 | 535 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2669 | 2734 | €-12,17 | 23,2% | 254 | 807 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
