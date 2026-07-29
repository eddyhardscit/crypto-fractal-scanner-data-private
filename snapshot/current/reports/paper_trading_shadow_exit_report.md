# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T05:53:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **578**
- Scenari virtuali ancora attivi: **8841**
- Gruppi in attesa dell'uscita originale: **187**
- Gruppi con originale chiuso ma Shadow ancora attive: **391**
- Confronti completati: **107384**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3012 | 3077 | €-1,85 | 46,7% | 637 | 477 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3003 | 3068 | +€8,71 | 51,6% | 873 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3003 | 3068 | +€7,05 | 50,6% | 875 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3003 | 3068 | +€4,50 | 48,5% | 972 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2996 | 3061 | +€4,99 | 49,2% | 882 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2994 | 3059 | +€3,50 | 48,9% | 827 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2971 | 3036 | +€6,38 | 44,3% | 694 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2971 | 3036 | +€4,49 | 43,9% | 671 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2971 | 3036 | +€4,34 | 42,1% | 762 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2971 | 3036 | +€2,92 | 43,2% | 586 | 192 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2970 | 3035 | €-1,73 | 39,4% | 371 | 720 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2969 | 3034 | +€1,14 | 41,1% | 508 | 354 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2965 | 3030 | €-1,70 | 32,5% | 364 | 654 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2925 | 2990 | €-2,34 | 29,8% | 306 | 757 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2925 | 2990 | €-4,93 | 32,8% | 169 | 917 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2894 | 2959 | +€4,84 | 33,2% | 410 | 330 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2849 | 2914 | €-6,32 | 27,9% | 255 | 786 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2839 | 2904 | +€4,27 | 36,8% | 198 | 511 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2802 | 2867 | €-6,15 | 33,5% | 520 | 563 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2725 | 2790 | €-12,16 | 22,8% | 254 | 836 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
