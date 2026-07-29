# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T01:54:24+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **671**
- Scenari virtuali ancora attivi: **11414**
- Gruppi in attesa dell'uscita originale: **250**
- Gruppi con originale chiuso ma Shadow ancora attive: **421**
- Confronti completati: **104340**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2945 | 3010 | €-2,32 | 46,3% | 632 | 457 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2939 | 3004 | +€8,52 | 51,5% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2939 | 3004 | +€6,89 | 50,5% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2939 | 3004 | +€4,31 | 48,3% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2932 | 2997 | +€4,81 | 49,0% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2930 | 2995 | +€3,37 | 48,7% | 805 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2929 | 2994 | €-2,23 | 39,2% | 371 | 720 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2907 | 2972 | +€6,39 | 44,3% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2907 | 2972 | +€4,53 | 44,1% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2907 | 2972 | +€4,25 | 42,0% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2907 | 2972 | +€3,01 | 43,5% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2905 | 2970 | +€1,25 | 41,4% | 486 | 354 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2896 | 2961 | €-4,98 | 33,1% | 169 | 914 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2887 | 2952 | €-2,10 | 32,8% | 360 | 621 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2871 | 2936 | €-2,28 | 30,3% | 306 | 727 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2842 | 2907 | +€4,74 | 33,1% | 403 | 329 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2806 | 2871 | €-6,36 | 28,3% | 255 | 767 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2783 | 2848 | +€4,36 | 37,2% | 196 | 495 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2743 | 2808 | €-6,23 | 33,6% | 509 | 539 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2676 | 2741 | €-12,12 | 23,2% | 254 | 811 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
