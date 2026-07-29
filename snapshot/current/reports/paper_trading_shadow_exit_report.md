# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T23:23:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **472**
- Scenari virtuali ancora attivi: **6667**
- Gruppi in attesa dell'uscita originale: **143**
- Gruppi con originale chiuso ma Shadow ancora attive: **329**
- Confronti completati: **110137**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3056 | 3121 | €-1,19 | 40,5% | 373 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3056 | 3121 | €-1,64 | 46,8% | 642 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3055 | 3120 | €-4,74 | 32,6% | 169 | 979 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3044 | 3109 | +€8,94 | 51,9% | 874 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3044 | 3109 | +€7,28 | 50,9% | 876 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3044 | 3109 | +€4,78 | 48,8% | 973 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3037 | 3102 | +€5,23 | 49,5% | 883 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3035 | 3100 | +€3,74 | 49,2% | 828 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3028 | 3093 | +€6,32 | 43,8% | 694 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3028 | 3093 | +€4,45 | 43,4% | 671 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3028 | 3093 | +€4,32 | 41,6% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3028 | 3093 | +€2,91 | 42,7% | 586 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3026 | 3091 | +€1,15 | 40,7% | 508 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3021 | 3086 | €-1,67 | 32,2% | 364 | 656 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3005 | 3070 | €-2,04 | 29,7% | 307 | 769 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2999 | 3064 | +€4,70 | 33,1% | 410 | 357 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2942 | 3007 | +€4,09 | 36,5% | 198 | 540 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2932 | 2997 | €-6,17 | 27,7% | 256 | 804 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2863 | 2928 | €-6,38 | 33,6% | 524 | 588 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2830 | 2895 | €-11,79 | 22,5% | 255 | 879 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
